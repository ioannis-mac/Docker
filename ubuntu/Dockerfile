FROM ubuntu
WORKDIR /aname
RUN apt-get update && apt-get upgrade -y
RUN apt install software-properties-common -y
RUN apt-get update
#RUN apt-get install python3.10 -y
COPY aScript.sh .
RUN chmod +x aScript.sh
CMD ["sh", "aScript.sh"] 