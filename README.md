# aye
![image]()
# I'm a js creator. 
## This is example of my code:
```javascript
	$.ajax('http://www.boredapi.com/api/activity/?${params}', {
		success:function(result){
			$('#result').show();
			let html=`
				<p>
					activity:${result.activity}
				</p>
				<p>
					price:${result.price}
				</p>
				<p>
					type:${result.type}
				</p>
			`
			$('#result').html(html);
			$('#but1').html('randomaze again')

		},
		error:function(xhr){
			console.log(xhr.statusText)
		}
	})
```
