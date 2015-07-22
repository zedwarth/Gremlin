FROM java:8

ENV VERSION 0.9.0-M2-hadoop1

RUN curl -O http://s3.thinkaurelius.com/downloads/titan/titan-$VERSION.zip && \
    unzip titan-$VERSION.zip && \
    rm -fr titan-$VERSION.zip

WORKDIR titan-$VERSION

COPY gremlin-server.yaml conf/gremlin-server/

CMD ./bin/gremlin-server.sh
