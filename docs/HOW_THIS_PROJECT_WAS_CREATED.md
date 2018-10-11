# How this project was created

This document details how this project was created.



# Create an empty repository on Github

Create the empty Github repository as: SoftDevJohn/my-simple-git-maven-project and get the address as:

https://github.com/SoftDevJohn/my-simple-git-maven-project.git



# Create a maven project on my Computer

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



# Add the maven project to a local git Repository

cd \dev\my-simple-git-maven-project

`git init`

*This creates the local git repository .git in the current directory.*

`git add .`

*Stage all the files in the current directory.*

`git commit -m "First commit"`

*All the local staged files are not committed to the local repository.*



git remote add origin https://github.com/SoftDevJohn/my-simple-git-maven-project.git

*This adds the URL for the remote repository where the local repository will be pushed.*



`git remote -v`

*This verifies that the remote origin has been added.*



`git push origin master`

*Pushes the changes in your local repository to Github.*



Now goto the Github website to verify that the local repository has been pused to git hub at: https://github.com/SoftDevJohn/my-simple-git-maven-project



