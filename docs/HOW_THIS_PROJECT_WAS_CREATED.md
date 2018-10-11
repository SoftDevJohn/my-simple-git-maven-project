Create a repositor

Create an empty GIT hub repository as:

SoftDevJohn/my-simple-git-maven-project and get the address as:

https://github.com/SoftDevJohn/my-simple-git-maven-project.git







# Create a maven project on Computer

Create the Maven project as:

C:\dev\\my-simple-git-maven-project\

`src\`

`main\`

​    java\

​        com\example\Greater.java

`site\`

​    apt\

​        index.apt

​    fml\

​        faq.fml

​    site.xml



`test\`

​    java\

​        com\example\TestGreater.java

/docs

`.gitignore`

`pom.xml`



Add the maven project to a





Import into Eclipse as follows:

File>Import>Existing Maven Projects>Next

Root Directory: C:\Users\John\TestProjects\ScratchWorkspace\my-maven

[CHECK] /pom.xml

\>Finish



{This will add the files:

.classath

.project

and create the sub-directories:

.settings

target

and then build the project. 

}



Now put this project under GIT control:

Create a local repository for it

Eclipse>my-eclipse-git-maven>RC>Team>Share Project>Git>Next>

Repository>Create... C:\Users\John\git\my-eclipse-git-maven-project

\>Finish

Eclipse>my-eclipse-git-maven>RC>Team>Commit>

Drag all Unstaged changes files to Staged changes

Add a commit message







Now push it

\>Commit

Window>Show View>Git Repositories

Select my-eclipse-git-maven-project in the Git Repositories view>RC

\>Push Branch master>

Remote Name: origin

Location

URL: <https://github.com/SoftDevJohn/my-eclipse-git-maven-project.git>

Host: github.com

Repository Path: /SoftDevJohn/my-eclipse-git-maven-project.git

User: SoftDevJohn

Password: *******

\>Push