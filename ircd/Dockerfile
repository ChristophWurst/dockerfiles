FROM ubuntu:latest

RUN apt-get update && apt-get install ngircd -y && apt-get clean

EXPOSE 6667

USER irc

ENTRYPOINT [ "ngircd", "-n" ]
