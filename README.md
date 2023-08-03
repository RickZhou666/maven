# maven
maven tips


## Commands
```bash
#  build jar locally 
mvn -s ~/.m2/settings-raptor.xml clean compile install -DskipTests -Dcobertura.skip -Prelease -DskipClassConflictsReporter=true -Denforcer.skip=true -Djacoco.skip=true -U -f pom.xml


#  2. find dependency 
mvn dependency: resolve

#  3. skip tests 
mvn clean install -DskipTests

#  4. force to check dependecy and download 
mvn clean install -U

```

<br><br><br>

## Operations
### 1. push local snapshot to remote repo
1. click deploy for your target project

2. make sure your repo link is correct in settings.xml

