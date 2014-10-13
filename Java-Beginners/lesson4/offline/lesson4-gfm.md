Welcome back, BD here.

So today we'll have a look at variables in Java.

Many of you may already know what variables are from math class.

A variable is a named storage that a program can easily manipulate

For instance, we have the variable x, which has a value of 9. And on the other hand we have the variable y, which has a value of 1. Well, what happens when we take the variables x and y and add them together? We'll we have the sum of the two variables!

Here's an example...

=======================================

    package hello-var;
    public class HelloWorld-Variables {
        public static void main(String[] args) {
            // TODO Auto-generated method stub
            int x = 9;       //Declaring a value for x, y and adding them together
            int y = 1;
            int xy = x + y;
            System.out.println("Hello");  //Notice how you need to add quotation marks for text? 
                                       //You don't need to do so for variables
            System.out.println("Sum: "+xy); //Blending Text along with a variable
        }
    }

Homework:

Please try and create a simple Java Application where you add two variables and print it. 
