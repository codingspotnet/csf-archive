Hey there, BroEd Here.

So in the last 2 lessons of Java Beginners, BD has shown you the basics of Java. Today we will really delve into the realms of Java. How should we start? Writing a Hello World program of course!

First, open up Eclipse and create a new Java project, like so:

![New Java Project](https://raw.githubusercontent.com/CodingSpot/Java-Beginners/master/lesson3/imgs/new-java-project.png)

Next, create a Java package. Java packages are like modules in a way.

![New Java Package](https://raw.githubusercontent.com/CodingSpot/Java-Beginners/master/lesson3/imgs/new-java-package.png)

Now, create a Java class. Java classes are individual source files in a package. Think of it like parts of different modules.

![New Java Class](https://raw.githubusercontent.com/CodingSpot/Java-Beginners/master/lesson3/imgs/new-java-class.png)

Now, we should go to the source code page. If you noticed carefully, there should be some lines like so:

    package hello;
    public class HelloWorld {
        public static void main(String[] args) {
            // TODO Auto-generated method stub`
That may seem like gibberish at first sight. Later we will learn to decode this arcane language, but for now, I will translate:

```package hello;``` - This source file is part of the package ```hello```.

```public class HelloWorld {``` - This is the start of the class ```HelloWorld```.

```public static void main(String[] args) {``` - Think of this as the ```int main()``` in C.

```// TODO Auto-generated method stub``` - ```//``` means a comment in Java. This particular comment means the lines above are auto-generated.

After some tinkering, it should look like this:

    package hello;
    public class HelloWorld {
        public static void main(String[] args) {
            // TODO Auto-generated method stub
            System.out.println("Hello World!");
        }
    }
Time for some more translating. I will decode the Hello World line for you:

```System``` means the command is part of the system.

```out``` means the command's output goes to standard out (your screen).

```println``` means the command will print the words in the parentheses and a newline.

Notice how in Java, you must terminate a command with a semicolon.

Now, hit Ctrl-F11 and watch the magic.
![HelloWorld Test Run](https://raw.githubusercontent.com/CodingSpot/Java-Beginners/master/lesson3/imgs/hello-test-run.png)

Voilà! The program has successfully executed and printed the words "Hello World!". Just as we anticipated.

For homework tonight, you should look up why the package, the class, and further subclasses are separated with periods. I'll see you around.
