# Maven Multi-Module Project

This repository demonstrates a basic Maven multi-module project structure with three modules:

- **core**: Contains core functionality.
- **service**: Contains service layer logic.
- **web**: Contains web layer logic.

## Structure

```
pom.xml
README.md
core/
	pom.xml
	src/main/java/com/uglyeagle/core/Core.java
service/
	pom.xml
	src/main/java/com/uglyeagle/service/Service.java
web/
	pom.xml
	src/main/java/com/uglyeagle/web/Web.java
```

## Building the Project

To build all modules, run:

```
mvn clean install
```

## Usage

Each module can be developed and tested independently. The parent `pom.xml` manages dependencies and module relationships.

## License

This project is licensed under the MIT License.
