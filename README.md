# Java Project: A Letter to Yourself (ISM3254)


-------

# Description <a name="description">

Write a program that displays your name and address on the screen as if it were a letter. Your
output should look something like that below. Use appropriate variables to store your name,
street address, city, and zip code.

<p align="center">
Example: <br/>
<img src="https://i.imgur.com/33RmseL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

# My Answer  <a name="scenario">

```ruby
// Nicholas Ospina
public class LetterToYourself {
public static void main(String[] args) {
String name = "Nicholas Ospina";
String streetaddress = "1234 UF Street";
String city = "Gainesville";
String state = "Florida";
String zipcode = "32608";
System.out.println("+----------------------------------------+");
System.out.println("| ####|");
System.out.println("| ####|");
System.out.println("| ####|");
System.out.println("|" + " " + name + " " + "|");
System.out.println("|" + " " + streetaddress + " "
+ "|");
System.out.println("|" + " " + city + ", " + state + " " + zipcode
+ " " + "|" );
System.out.println("| |");
System.out.println("+----------------------------------------+");
}
}

```
