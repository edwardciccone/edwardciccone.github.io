---
layout: post
title: Tutorial - Building a Simple JavaFX Application
subtitle: Lets learn how to use JavaFX
---
The purpose of this tutorial is to understand the concepts of JavaFX and what actually happens behind the scenes. Learning something from the inside out has created the strongest foundations for me when learning a new technology.  

My goal is to help you construct a solid base for JavaFX and set you on the right path to develop effecient and reusable software. 

The goal of this tutorial is to build a simple JavaFX application but _more importantly, to learn the concepts and architecture of a JavaFX Application_.  
  
Learning JavaFX from the inside out will help you grasp it way more effectively then if you just learned the syntax. Doing it this way, is the only way to do it.  

### Prerequiests
- Java 8 installed on your local machine
- Familiar with the Netbeans IDE
- Intermediate experience in Java

### Step 1 - Configuring the IDE
If you wish to use Netbeans and do not currently have it installed, you can download it [here](https://netbeans.org/downloads/index.html), choose either the Java SE or Java EE version. Download it, extract it, and open up Netbeans.  

If you already have it installed, make sure it is Netbeans v8.2 (recommended version as of December 2016).  

Once Netbeans is open navigation to _File -> New Project_. Under categories, select JavaFX, and then under Projects select JavaFX Application. Click next, and enter **MyFirstFx** for the name. Click finish and the project will be generated.  

Netbeans by default creates a basic JavaFX application, but for the purpose of this tutorial erase the generated code so that your **MyFirstFx.java** file looks like mine below.

```java
package myfirstfx;

import javafx.application.Application;
import javafx.scene.Scene;
import javafx.stage.Stage;

public class MyFirstFx extends Application {

  @Override
  public void start(Stage primaryStage) {

  }

  public static void main(String[] args) {
    launch(args);
  }

} 
```

The main class of any JavaFX application
