FROM: ubuntu:16.04

RUN apt update && apt install -y curl nano wget git-core openssh-server build-essential

RUN 

EXPOSE 22

CMD ssh -D
