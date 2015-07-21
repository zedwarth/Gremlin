FROM java:8

RUN curl -O http://s3.thinkaurelius.com/downloads/titan/titan-0.5.4-hadoop2.zip
RUN unzip titan-0.5.4-hadoop2.zip

WORKDIR titan-0.5.4-hadoop2
CMD ./bin/gremlin.sh
