# maven_java
1️⃣ Check Maven Version
Steps

Press Windows + R

Type: cmd

Click OK

Type:

mvn -version


Press Enter

If you get 'mvn' not recognized → Maven not installed or PATH not added.

2️⃣ Create Maven Java Project (Using Eclipse)
Steps

Open Eclipse IDE

On top menu → click File

Click New

Click Project…

Expand Maven

Click Maven Project

Click Next

Check Create a simple project (skip archetype selection)

Click Next

Fill details:

Field	Value
Group Id	maven_java
Artifact Id	java_maven
Version	0.0.1-SNAPSHOT
Packaging	jar

Click Finish

3️⃣ Maven Java Project Structure (as shown in PDF)

In Project Explorer, you will see:

src/main/java  
src/test/java  
pom.xml  


No action needed — Eclipse creates it automatically.

4️⃣ Run the Java Program (Output in PDF)
Steps

Right-click src/main/java

Click New → Class

Enter:

Name: Demo     click:finish

Paste sample code:

public class Demo {
    public static void main(String[] args) {
        System.out.println("Maven Java Project");
    }
}        save with ctrl+s


Right-click on the file → Run As → Java Application     ---->>>MAVEN_JAVA
Click New Repository (green button or “+” → “New repository”)   

 Click Create Repository   Open your project folder in Terminal / PowerShell      
 git init                                                                                                      
 git add .
 git commit -m "Initial Maven project commit"                                                                                  
 git remote add origin https://github.com/Navya-0408/my-maven-java-project.git     
 git branch -M main
git push -u origin main
 DONE
-------------------
maven web
