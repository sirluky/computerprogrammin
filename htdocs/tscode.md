Typescript
<pre class="stretch typescript"><code data-trim>

// This is code for telling you hello and length of your name

function sayHello(name:string){
	var namelength:number = name.length;
	var hello = `Hello ${name}, your name is ${namelength} characters long`;
	if(name == 'Lukas'){
	hello = hello + ', you are awesome';
	}
	return hello
}

var name: string;

do {
	name = prompt('Tell me your name')
	alert(sayHello(name));
} while(name !== "")

alert('Bye');

</code></pre>