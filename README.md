# ConsoleDrawingApp
A simple console version of a drawing program. 

# Tools used
Java 8
Junit 5
Collections framework
Factory Design pattern
Maven
Eclipse

# Requirements

Command 		    Description
C w h           Should create a new canvas of width w and height h.
L x1 y1 x2 y2   Should create a new line from (x1,y1) to (x2,y2). Currently only
                horizontal or vertical lines are supported. Horizontal and vertical lines
                will be drawn using the 'x' character.
R x1 y1 x2 y2   Should create a new rectangle, whose upper left corner is (x1,y1) and
                lower right corner is (x2,y2). Horizontal and vertical lines will be drawn
                using the 'x' character.
B x y c         Should fill the entire area connected to (x,y) with "colour" c. The
                behavior of this is the same as that of the "bucket fill" tool in paint
                programs.
Q               Should quit the program.

Steps to run

Method 1:

1. Open ConsoleDrawingApp\src directory in command prompt
2. Generate jar file by running "mvn clean package" command 
3. Run java -jar target/ConsoleDrawingApp-0.0.1-SNAPSHOT
4. Now run java App.java

Method 2: 
1. Open project in Eclipse
2. Right click on pom.xml file and run maven install
3. Once build is successful, Right click on App.java and select Run As --> Java Application
