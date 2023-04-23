# Lab Report 2 
**by Rosario Ortiz**

## Part 1 - Writing a Web Server 

For this portion of the lab, I used a lot of the code given for writing a server during lab 2. The Server.java file is the same, but I created a new StringServer.java file which adapted code from NumberServer.java. The adapted code is given below:  

```
//most of this code is taken from lab 2's NumberServer. 

import java.io.IOException;
import java.net.URI;

class Handler implements URLHandler {

    public String handleRequest(URI url) {
        if (url.getPath().equals("/add-message")) {
            String q = url.getQuery();
            q = q.substring(2);
        
            return (q) ; 
        }
        else {
            System.out.println("Path: " + url.getPath());
            return "404 Not Found!";
        }
    }
}

class StringServer {
    public static void main(String[] args) throws IOException {
        if(args.length == 0){
            System.out.println("Missing port number! Try any number between 1024 to 49151");
            return;
        }

        int port = Integer.parseInt(args[0]);

        Server.start(port, new Handler());
    }
}

```

![Screenshot of server printing the formatted query "Please give me an A !"](images/server_ss1.png)<!--- Code-->

The methods in my code that are called include:
- the main method in StringServer.java,
- start in Server.java
- handleRequest in StringServer.java
- handle in Server.java


What are the relevant arguments to those methods, and the values of any relevant fields of the class?
How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.  

![Screenshot of server printing an error message](images/server_ss2.png)

Which methods in your code are called?
What are the relevant arguments to those methods, and the values of any relevant fields of the class?
How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.

## Part 2 - Debugging During Lab 3

Choose one of the bugs from lab 3.

Provide:

A failure-inducing input for the buggy program, as a JUnit test and any associated code (write it as a code block in Markdown)
An input that doesn’t induce a failure, as a JUnit test and any associated code (write it as a code block in Markdown)
The symptom, as the output of running the tests (provide it as a screenshot of running JUnit with at least the two inputs above)
The bug, as the before-and-after code change required to fix it (as two code blocks in Markdown)
Briefly describe why the fix addresses the issue.


## Part 3 - New Things I Learned

In a couple of sentences, describe something you learned from lab in week 2 or 3 that you didn’t know before.



