FROM ubuntu:20.04

RUN apt -y update && apt -y upgrade
RUN apt install -y curl

COPY search.sh .
RUN chmod +x search.sh

CMD ./search.sh
