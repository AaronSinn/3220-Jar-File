# 3220-Jar-File
This repo holds the jar file for 3220's assignment 1.

# Eclipse Set-up
1. Downlaod the JAR file
2. In Eclipse, create a new project if you have not already done so.
3. Add the JAR to your build path.
  a. Right click your project
  b. Click ```Build Path``` then ```Configure Build Path```
  c. Click on ```Libaries``` and then ```Classpath```
  d. Click ```Add External JARs...``` and then selected the JAR file you downloaded
  e. Apply and Close
4. You should now see the JAR under ```Referenced Libraries``` in your project. Your project structrue should look simialr to the example below.
5. Delete the file
```module-info.class```
7. Import the classes into your project
``` bash
import assignmentOne3220.*;
```
