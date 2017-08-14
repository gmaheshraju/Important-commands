# Important-commands

1)Command to find files from windows command prompt

So if you want to find files with a given extension in windows, this is how you would do:

$> where /r . *.java

output:

C:\Users\C5253526\ws\PrerequisiteOOP\src\tiny\world\Earth.java
C:\Users\C5253526\ws\PrerequisiteOOP\src\tiny\world\Human.java
C:\Users\C5253526\ws\Project1\src\Test.java
C:\Users\C5253526\ws\Project2\src\Test2.java
C:\Users\C5253526\ws\test\src\test\BooleanSyn.java
C:\Users\C5253526\ws\test\src\test\DateT.java
C:\Users\C5253526\ws\test\src\test\Test.java
C:\Users\C5253526\ws\test\src\test\TestDateCalendar.java


2)Command to copy all the notepads with .txt extensions into single notepad file.

$> copy /b *.txt all_text_files_data_into_single_text_file.txt
