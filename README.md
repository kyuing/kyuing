## Hello there 👋

<br />


```java
import java.util.LinkedHashMap;

/**
 * @author Kyu
 */
public class Main {
	public static void main(String[] args) {

		new Hello().print();
		
	}
}

class Hello {
	public void print() {
		
		LinkedHashMap<String, String> map = new LinkedHashMap<>();
		map.put("Name", "KyuTae Han");
		map.put("Languages", "English, Korean");
		map.put("Code","HTML/CSS, Javascript, Java");
		map.put("Tool/FW", "nodeJS, ajax");
		map.put("Database", "mongoDB, MySQL");
		map.put("Interests", "web, RESTful, test/QA, project mgmt, SE");
		
		map.forEach((k, v) -> System.out.println(k + ": " + v));	// insertion-order
	}
}
```

```bash
Name: KyuTae Han
Languages: English, Korean
Code: HTML/CSS, Javascript, Java
Tool/FW: nodeJS, ajax
Database: mongoDB, MySQL
Interests: web, RESTful, test/QA, project mgmt, SE
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
