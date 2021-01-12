FROM ubuntu:16.04
RUN apt-get update && apt-get install -y curl
WORKDIR /scripts
COPY curler.sh .
CMD [ "/scripts/curler.sh"]