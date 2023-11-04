# An executable JAR project
> **With an introduction to Maven - by Kornel Filep | EPAM System**
### [Open source code](https://github.com/Cokode/maven-project/tree/main/src/main/java/com/country/demo)
```

This is a 'hello-world.jar' file, which is an executable JAR (Java Archive) application.
When executed, it prompts the user to input their name and select a language. 
After receiving this input, the application greets the user in the chosen language. 
It supports three languages, including Hungarian.

If the language is unknown, it writes an error.
If the user does not specify a language, the Hungarian language is used by default.

Example input and output:
java -jar hello-world.jar Csaba -> Hello Csaba!
java -jar hello-world.jar Csaba hun -> Hello, Csaba!
java -jar hello-world.jar Csaba eng -> Hello, Csaba!
java -jar hello-world.jar Csaba haw -> Aloha, Csaba!

```
