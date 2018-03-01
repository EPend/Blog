# Fourth Week

This week I updated the class diagram to the latest version, splitting up several functions in to classes and figuring 
out a ways each class will interact with each other in the finished game.

![class diagram](https://gitlab.dcs.aber.ac.uk/mof11/GP8/raw/cab48afa14de13f093e4daa7380628102b0da30c/docs/Class_diagram.png)

During our tuesday group meeting we brought up that the letter Q had to be Qu in the cube, I made several changes
and changed the data type from Character to String and added a clause for changing Q to Qu during randomisation.

```java
String temp = String.valueOf(alphabet.charAt(rand.nextInt(alphabet.length())));
if(temp.equals("Q")) {
    temp = "Qu";
}
cube.put(i, temp);
```