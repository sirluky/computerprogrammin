Javascript
<pre class="stretch javascript"><code data-trim>

    // This is code for telling you hello and length of your name

    function sayHello(name){
        var namelength = name.length;
        var hello = `Hello ${name}, your name is ${namelength} characters long`;
        if(name == 'Lukas'){
            hello = hello + ', you are awesome';
        }
        return hello
    }

    var name; 

    do {
        name = prompt('Tell me your name')
        alert(sayHello(name));
        
    } while(name !== "")

    alert('Bye');

   </code></pre>