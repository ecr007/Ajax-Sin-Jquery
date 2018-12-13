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
