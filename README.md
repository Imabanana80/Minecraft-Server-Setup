# Minecraft Server Setup Stuff

A useful repo with a bunch of stuff to help setup minecraft servers on ubuntu (uses screen)

### Install Java (17)

```
apt-get update && apt-get upgrade && apt install openjdk-17-jdk openjdk-17-jre && java -version
```

### Download Server.jar

Get url from : https://papermc.io/downloads/paper

```
wget <download url from above>
```

### Run server for the first time

```
java -jar <filename>.jar
```

### Install Screen

```
apt update && apt install screen && screen -v
```
