FROM java:8

RUN curl -O https://www.apache.org/dist/incubator/tinkerpop/3.0.0-incubating/apache-gremlin-server-3.0.0-incubating-bin.zip
RUN unzip apache-gremlin-server-3.0.0-incubating-bin.zip
RUN mv apache-gremlin-server-3.0.0-incubating gremlin-server
RUN rm apache-gremlin-server-3.0.0-incubating-bin.zip

WORKDIR gremlin-server

CMD ./bin/gremlin-server.sh
