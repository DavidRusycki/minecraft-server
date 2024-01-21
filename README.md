# minecraft-server

This repository contains a initial struture to run a minecraft server into Docker containers.

## 1. First step

Download a server `.jar` file, to turn possible init the server into a docker container.

Possible link: https://minecraft.wiki/w/Java_Edition_1.8.9

## 2. Copy the server file

Copy a downloaded server file to ./artifacts diretory, with name `server.jar`.

## 3. Execute a docker container

The run a docker container, it's necessary you run the command `docker compose up -d`. This init the server and create a eula file. In this file you will change false value to a true value and re run the command to init a container.

## 4. Finish

very good, your server it should already running.

## 5. Next steps

You should research and read the Minecraft server documentation.