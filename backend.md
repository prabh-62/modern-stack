# 3. Backend

## Prequisities
> Please make sure you have all the [prequisites](prerequisites.md) configured before moving on.

Mature Backend frameworks:

<details>
<summary>Ruby on Rails API only</summary>

[Homepage](http://rubyonrails.org)

Imagine what you could build if you learned Ruby on Rails…

<img src="assets/brand/rails.svg" alt="Rails" width="200px" />

#### Prerequisites
```bash
ruby -v
```
```bash
sqlite3 --version
```

#### Getting started with Rails

> Install Rails framework
```bash
gem install rails
```

> How to create a new react project?
```bash
rails --version
```
```bash
rails new <project-name> \
    --api
    --skip-bundle
    --skip-git
    --skip-test-unit

```
> Open the project in IDE
```bash
code <project-name>
```

> Open integrated terminal inside vscode
 - <kbd>Ctrl + `</kbd>

> Install dependencies
```bash
bundle install
```

> Run project
```bash
rails server
```

> Rails Server should start on port 3000. Open chrome and type 'http://localhost:3000' if it doesn't automatically pop up

[Rails Guide](http://guides.rubyonrails.org/getting_started.html) 
</details>


<details>
<summary>ASP.NET Core WebAPI</summary>

[Homepage](https://www.microsoft.com/net)

ASP.NET is powerful frameowrk designed by microsoft to build web applications.

![ASP.NET](assets/brand/net.png)

To begin with ASP.NET Core

> Install .NET Core
- Follow instructions on [official website](https://www.microsoft.com/net/core#linuxubuntu)

> How to create a new react project?
```bash
dotnet -version
```
```bash
dotnet new webapi <project-name>
```

> Open the project in IDE
```bash
code <project-name>
```

> Open integrated terminal inside vscode
 - <kbd>Ctrl + `</kbd>

> Install dependencies
```bash
dotnet restore
```

> Run project
```bash
dotnet run
```

> By default, the solution will run on port 5000. Open google chrome and type 'http://localhost:8080/api/values' if it doesn't automatically pop up

### [Tutorials](https://mva.microsoft.com/)

</details>

</details>

<details>
<summary>Spring Boot REST API</summary>


[Homepage](https://spring.io)

Spring Boot by Pivotal (Java)

![Spring](assets/brand/spring.png)

### Prerequisites
```bash
java --version
```

### Getting started with Spring

> Install sdkman and other tools
```bash
curl -s "https://get.sdkman.io" | bash
```
```bash
# Install Spring Framework
sdk install springboot
```
```bash
# To run and download dependencies, we require gradle
sdk install gradle
```


> How to create a new Spring project?
```bash
spring version
```
```bash
spring init --list
```
```bash
spring init  \
    --build=gradle \
    --java-version=1.8 \
    --dependencies=web,data-jpa \
    --packaging=war \
    <project-name>
```
> Open the project in IDE
```bash
code <project-name>
```

> Open integrated terminal inside vscode
 - <kbd>Ctrl + `</kbd>

> Install dependencies
```bash
gradle dependencies
```

> Run project
```bash
gradle bootRun
```

> Spring project runs on port 8080. Open google chrome and type 'http://localhost:8080' if it doesn't automatically pop up

Browse some of more awesome [Pivotal Projects](https://spring.io/projects) 
</details>

</details>

# What to do next
[System Deign Primer](https://github.com/donnemartin/system-design-primer)

[Next: Devops](devops.md)

