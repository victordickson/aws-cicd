# aws-cicd
Demostratrating CICD on AWS using github actions.
This repository contains simple "hello world" program that was automatically deployed from code to cloud through Github Actions workflows. You can watch the demo on Twitch  https://www.twitch.tv/videos/1778017615

First, test locally by running the following. 

```
go run main.go

docker build -t hello .

docker run --rm -it --name hello -p 0.0.0.0:8080:8080 hello
