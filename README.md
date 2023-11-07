# Anatomy of Flutter 

## What is Widget ? 
> * `Avery Componets off the screen is define as a widget.`
> * Componets include text, buttons and different different shape which are beign display on the screen.
> * It does not include colors and decoration of componets.


## Material Design Introduction :
> * go to material design flutter (https://m3.material.io/develop/flutter)



### Body Structure App :

<pre>
    void main() {
      - methods
      - widgets
      - class
    }
</pre>


### Header File Flutter :

#### `--: Android :--` 
> * Material.dart
> * import 'package:flutter/material.dart';

#### `--: IOS :--` 
> * cupertino.dart
> * import 'package:flutter/cupertino.dart';


## Basic Flutter widgets (MaterialApp, SafeArea, Center, Text, Scaffold & AppBar widgets) :

### MaterialApp :
> * MaterialApp is a predefined class or widget in Flutter.
> * It's a core component of a Flutter app.
> * MaterialApp contains widgets that are used for the material design of an application.
> * The MaterialApp widget provides a wrapper around other Material Widgets.
> * We can access all the other components and widgets provided by Flutter SDK.

### SafeArea :
> *  It provides padding around app content to prevent overlap with system UI elements.

### Center :
> * Center widget comes built-in with flutter, it aligns its child widget to the center of the available space on the screen.

### Child : 
> * This property is used to store the child widget of the container.

### Text : 
> * A Text is a widget in Flutter that allows us to display a string of text with a single line in our application.

### Scaffold : 
> * The Scaffold widget in Flutter is used to create the basic visual layout structure for material design.
> * which provides many widgets or we can say APIs like Drawer, Snack-Bar, Bottom-Navigation-Bar, Floating-Action-Button, App-Bar, etc. 

### Appbar Widget :
> * Appbar widget is divide three main part.
> 1. Leading
> 2. Title
> 3. Action

<br>

## Widget Tree (using draw.io website) :

<p><img src = "https://github.com/SJaynesh/Co-Flutter-ch-04/assets/115562979/40ce03df-f4fd-41ee-a20c-af2ded45391c.png" width=60% height=50%></p>

<br><br>

## TextStyle class in detail :

<br>

<pre>
    body: Center(
            child: Text("$text\nI am Flutter developer",
              style: TextStyle(
                fontSize: 30,
                fontWeight: FontWeight.bold,
                color: txtColor,
                fontStyle: FontStyle.italic,
                decoration: TextDecoration.combine([
                  TextDecoration.underline,
                  TextDecoration.overline,
                ]),
                decorationStyle: TextDecorationStyle.dashed,
                decorationColor: Colors.red,
                decorationThickness: 3,
                letterSpacing: 5,
                wordSpacing: 5,
                overflow: TextOverflow.ellipsis,
              ),
            ),
          ),
</pre>

<br>

### Dumy Paragraph : `Lorem Ipsum`
### Color : `Color Palette` , `Ui Gradients`

<br><br>

## Colors Class : 

<br>

> * 1 Colors.red
> * 2 Colors.red.shade200
> * 3 Colors.red[400]
> * 4 Colors.red.withOpacity(0.8)
> * 5 const Color.fromRGBO(100, 100, 100, 1)
> * 6 const Color(0xff00000)

<br><br>

## Display content using variables & string interpolation :

> * That is, we can give text, color, etc. in the app from a variable.

<br>

<pre>
        Color appbarColor = const Color(0xffFFF2D8);
        Color bgColor = const Color(0xffBCA37F);
        Color txtColor = const Color(0xff113946);
    
        String appbarText = "Flutter App";
        String text = "Jaynesh 😊 Sarkar";
</pre>

<br><br>

## RichText() widget :
> * `The RichText widget displays text that uses multiple different styles.`
> * The text to display is described using a tree of TextSpan objects, each of which has an associated style that is used for that subtree.
> * Text property has to be given in RichText.
> * RichText has text color by default white.

<pre>
    
</pre>









