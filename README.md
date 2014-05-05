## Snippet ##
### Generate Ninja Project ###
mvn archetype:generate -DarchetypeGroupId=org.ninjaframework -DarchetypeArtifactId=ninja-servlet-archetype-simple

cd project

mvn clean install

### Compile ###
mvn compile

### Run Ninja Server ###
mvn ninja:run

### Add git remote ###
git remote add origin _URL_
