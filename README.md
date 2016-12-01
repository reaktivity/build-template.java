This is a build template for the Reaktivity Java projects.

After cloning your new Java project...
```
$ git config merge.ours.driver true
$ git remote add --track develop build https://github.com/reaktivity/build-template.java
$ git fetch build develop
$ git merge build/develop --no-commit
```
...then review the changes, modify the `pom.xml` to reflect your project name, description, and artifact id.

Finally, commit the changes.
```
$ git commit
```