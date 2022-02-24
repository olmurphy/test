# test

testing the .gitignore file to ignore compiled files ending in .class

## It works

Steps (I took):
1. create maven `mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false`
2. setup remote repository with `README.md` and '.gitignore' files
3. `$ cd my-app` and enter:
    1. `$ git init`
    2. `$ git pull <url_to_repository>`
    3. `$ git branch -b main` (bc github switched from master -> main)
