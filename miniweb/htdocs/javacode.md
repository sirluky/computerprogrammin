Java
<pre class="stretch"><code data-trim >
import java.util.Scanner;

class Main {

	public  static String sayHello(String name){
		int namelength = name.length();

		String hello = "Hello " + name + ", your name is " + namelength + " characters long";

		if("Lukas".equals(name)){
			hello = hello + ", you are awesome";
		}

		return hello;
	}

	public  static  void main(String[] args) {
		String name = "";

		Scanner myscanner = new Scanner(System.in);
		do {
		name = myscanner.nextLine();
		System.out.println(sayHello(name));

		} while(!"".equals(name));
	}
}
</code></pre>
