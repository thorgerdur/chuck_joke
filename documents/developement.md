# Development manual

### Build environment:

To run the program your machine must have *Java* environment and *Gradle* installed.

**Java:**

```
sudo apt-get update
sudo apt-get install
openjdk-7-jdk
```

**Java 8:**
```
sudo apt-get update
sudo apt-get install oracle-java8-installer

```

**Gradle:**

```
sudo apt-get install software-properties-common
sudo apt-apt-repository ppa:cwchien/gradle
sudo apt-get update
sudo apt-get install gradle

```
To check what version is installed, run gradle --version.
You should have version 2.8.

### Source control:

The team is using GitHub as a version control server.
The service provides Git based projects and every team member has to have a working git on their computer.
There is a great book online to learn more about git: [Pro Git book](http://git-scm.com/book)

Go to [our github page ](https://github.com/TheJamminGroovers/Sidannarverkefni) and fork the repository to your own account.

Open up console and clone our repository to your machine.
```
git clone https://github.com/TheJamminGroovers/Sidannarverkefni.git
```

Now the project is on your computer and can be edited.

### Testing:
For continuous integration we use Travis CI server.
To set up Travis go to [Travis-ci.org](https://travis-ci.org/) and sign in with your GitHub account.

You have to give GitHub access to the repository using sync and flicking the repository switch on.

Create a .travis.yml file in the root of the project and add a build badge into the top of the README.md file using
```
[![Build Status](your travis url for the repo here.svg)](your travis url for the repo)
```

Now every time you commit a change to your GitHub, Travis will build your project.

All unit tests are saved in the folder Sidannarverkefni/src/test/java/is/xperienz/tictactoe

### Documentation

All the documentation is written in the text editor Atom.
It is very convenient to see how the rendered html is going to look like using the preview function.

All three manuals/reports are located in the [Sidannarverkefni/Documents](https://github.com/TheJamminGroovers/Sidannarverkefni/documents) folder, including pdf formats of the documentation.

### Coding conventions

We use a coding analysis server [Codacy](https://www.codacy.com/) to track our changes from GitHub and tell us the quality of our code.

Some of the coding conventions that we follow are:

1. Curly brackets go to the same line
2. Pascal casing for classes
3. Camel casing for functions

