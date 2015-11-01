# Administration manual

To run the program your machine must have *Java* environment and *Gradle* installed.

## Get the project

Set up git on your computer.

Go to [our github page ](https://github.com/TheJamminGroovers/Sidannarverkefni) and fork the repository to your own account.

Open up console and clone the repository to your machine.
```
git clone https://github.com/TheJamminGroovers/Sidannarverkefni.git
```

Now the project is on your computer.

#### Build the project with Gradle
```
gradle build  or
./gradlew build
```
The output will be "Build successful" or "Build failed"


#### Run the project

Run the jar file you just built
```
java -jar build/libs/TicTacToe-1.0.jar
```
The jar file is located in the libs directory inside the libs directory.

