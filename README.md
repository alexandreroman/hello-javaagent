# Hello Java agent

This project shows how to create a Java agent.

Compile this project using a JDK 8+:
```bash
$ ./mvnw clean package
```

You can then use this Java agent with your app:
```bash
$ java -javaagent:<PATH>/hello-javaagent-1.0.0.jar -jar yourapp.jar
Hello world, from Java Agent!
```

## Contribute

Contributions are always welcome!

Feel free to open issues & send PR.

## License

Copyright &copy; 2019 [Pivotal Software, Inc](https://pivotal.io).

This project is licensed under the [Apache Software License version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
