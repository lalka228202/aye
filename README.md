# aye
![this is img](https://static.wikia.nocookie.net/minecraft_ru_gamepedia/images/5/56/%D0%94%D1%83%D0%B1_JE12.png/revision/latest/scale-to-width-down/1200?cb=20210523095035)
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
