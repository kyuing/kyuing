## Hello there 👋

<br />


```java
import java.util.LinkedHashMap;

/**
 * @author Kyu
 */
public class Main {
	public static void main(String[] args) {
		
		Hello hello = new Hello();
		hello.print();	
		
	}
}

class Hello {
	public void print() {
		
		LinkedHashMap<String, String> map = new LinkedHashMap<>();
		map.put("Name", "KyuTae Han");
		map.put("Languages", "English, Korean");
		map.put("Interests", "HTML, Javascript, nodeJS, web dev, RESTful, mongoDB, Java");

		map.forEach((key, value) -> System.out.println(key + ": " + value));	// insertion-order
	}
}
```

```
//output
Name: KyuTae Han
Languages: English, Korean
Interests: HTML, Javascript, nodeJS, web dev, RESTful, mongoDB, Java
```

<br />

## Contact
- [email] 
- [linkedin]


<!-- links -->
[email]: mailto:kyykyu000@gmail.com
[linkedin]: https://www.linkedin.com/in/kyutae-han-b86523104/ 

<!--
**kyuing/kyuing** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
