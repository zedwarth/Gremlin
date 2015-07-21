FROM java:8

RUN curl -O https://www.apache.org/dist/incubator/tinkerpop/3.0.0-incubating/apache-gremlin-console-3.0.0-incubating-bin.zip
RUN unzip apache-gremlin-console-3.0.0-incubating-bin.zip

RUN mv apache-gremlin-console-3.0.0-incubating gremlin-console
RUN rm apache-gremlin-console-3.0.0-incubating-bin.zip

WORKDIR gremlin-console

CMD ./bin/gremlin.sh
