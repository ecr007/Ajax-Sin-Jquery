# Ajax-Sin-Jquery


```javascript
const Http = new XMLHttpRequest();
const url='https://jsonplaceholder.typicode.com/posts';

Http.open("GET", url);
Http.send();

Http.onreadystatechange=(e)=>{

	// this.status == 200
	console.log(Http.responseText)
}
```

# POST Request

```javascript
const Http = new XMLHttpRequest();
			
const url = 'http://caricole-landing.lc/send.php';

Http.open("POST", url);
Http.setRequestHeader('Content-type', 'application/x-www-form-urlencoded');

var params = "fistname=&lastname=&email=";

Http.send(params);

Http.onreadystatechange=(e)=>{

	// this.status == 200
	console.log(Http.responseText);
}
```
