---
layout: post
title: Tutorial: Building a Simple JavaFX Application
subtitle: Understanding the concepts of building a JavaFX Application and what goes on behind the scenes
---

### Introduction
JavaFX is a very powerful library for building UI Applications in pure Java. The goal of this tutorial is to build a simple application using JavaFX as well as grasp the concepts of JavaFX so you can start building your own JavaFX applications.  
I will show you how to configure your IDE environment, teach you step by step how to make a basic applications, and describe to you some best practices and concepts of JavaFX.

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
