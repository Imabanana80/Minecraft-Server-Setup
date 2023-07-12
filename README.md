# Minecraft Server Setup Stuff

a repository with a bunch of commands and stuff to help setup minecraft servers easily and quickly

## Basic Server Setup

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

### Download start.sh

```
wget https://raw.githubusercontent.com/Imabanana80/Minecraft-Server-Setup/main/files/start.sh
```

### Install Screen

```
apt update && apt install screen && screen -v
```
