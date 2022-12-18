# **Language General Questions**

## *Currently for conviniency, all these question and answeres were created by openAI's ChatGBT*


1. What are some of the key differences between Kotlin and Java?

	* **Syntax:** Kotlin has a more concise syntax than Java, making it easier to read and write. It also has several features that Java does not have, such as type inference and the ability to use higher-order functions.

	* **Null safety:** Kotlin has a built-in null safety feature that helps prevent null reference exceptions. In Kotlin, all variables must be explicitly marked as nullable or non-nullable, which helps catch potential null reference issues at compile time.

	* **Exception handling:** Kotlin's exception handling is more concise than Java's. In Kotlin, the try-catch block is an expression that can be used as part of a larger expression, whereas in Java it is a standalone statement.

	* **Data classes:** Kotlin has a feature called data classes, which allows you to define a class that holds data without having to write any additional code. This can be a convenient way to create simple classes that are used to store and pass data around in your code.

``` java
// Java Way
public class Person {   
    private String name;
    private int age;
    
    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }

    public void setName(String name) {
        this.name = name
    }

    public int getAge(String age) {
        this.age = age
    }
}
```

``` kotlin
// Kotlin Way
data class Person(
    val name: String,
    val age: Int;
)
```

Type conversions: Kotlin has a more powerful type conversion system than Java. It has built-in support for implicit and explicit type conversions, as well as support for operator overloading.

Interoperability: Kotlin is designed to be fully interoperable with Java, which means that you can use Kotlin code in a Java project and vice versa. This can make it easier to migrate an existing Java codebase to Kotlin or to use a mix of both languages in the same project.
	


2. In what situations might you choose to use Kotlin over Java, or vice versa?
3. How does Kotlin's syntax differ from Java's syntax?
4. What are some of the features of Kotlin that make it a more modern programming language compared to Java?
5. How does Kotlin's type inference system compare to Java's?
6. How does the null safety feature in Kotlin compare to the null safety feature in Java?
7. How does the way that Kotlin handles exceptions compare to the way Java handles exceptions?
8. How does the way that Kotlin handles data classes compare to the way Java handles data classes?
9. How does the way that Kotlin handles type conversions compare to the way Java handles type conversions?
10. In what ways has Kotlin been designed to be more concise and expressive than Java?