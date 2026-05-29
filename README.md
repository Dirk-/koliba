# koliba
This repository is just for learning purposes.

This is an Apache Ant / NetBeans project. You can compile it with:

````
cd AnagramGame
ant compile
````
Or to build the full JAR and run it:
````
cd AnagramGame
ant jar
java -jar dist/anagrams.jar
````

The build.xml at the project root drives the build. The compiled classes will appear in build/classes/.

If you don't have Ant installed, you can install it via Homebrew (macOS):

````
brew install ant
````

or Winget (Windows):

````
winget install Apache.Ant
````
