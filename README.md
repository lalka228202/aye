# aye
![image]([https://commons.wikimedia.org/wiki/File:Aluminium-thugun.JPG#/media/Файл:Aluminium-thugun.JPG](https://www.google.com/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2Fd%2Fd5%2FAluminium-thugun.JPG%2F222px-Aluminium-thugun.JPG&tbnid=Oa_j42tVHX2tZM&vet=12ahUKEwiyvsPr1r6CAxWPif0HHS34A04QMygBegQIARBw..i&imgrefurl=https%3A%2F%2Fru.wikipedia.org%2Fwiki%2F%25D0%25A7%25D1%2583%25D0%25B3%25D1%2583%25D0%25BD_(%25D0%25BF%25D0%25BE%25D1%2581%25D1%2583%25D0%25B4%25D0%25B0)&docid=tnz2OsIkEoiR6M&w=222&h=270&q=%D1%87%D1%83%D0%B3%D1%83%D0%BD&ved=2ahUKEwiyvsPr1r6CAxWPif0HHS34A04QMygBegQIARBw)https://www.google.com/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2Fd%2Fd5%2FAluminium-thugun.JPG%2F222px-Aluminium-thugun.JPG&tbnid=Oa_j42tVHX2tZM&vet=12ahUKEwiyvsPr1r6CAxWPif0HHS34A04QMygBegQIARBw..i&imgrefurl=https%3A%2F%2Fru.wikipedia.org%2Fwiki%2F%25D0%25A7%25D1%2583%25D0%25B3%25D1%2583%25D0%25BD_(%25D0%25BF%25D0%25BE%25D1%2581%25D1%2583%25D0%25B4%25D0%25B0)&docid=tnz2OsIkEoiR6M&w=222&h=270&q=%D1%87%D1%83%D0%B3%D1%83%D0%BD&ved=2ahUKEwiyvsPr1r6CAxWPif0HHS34A04QMygBegQIARBw)
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
