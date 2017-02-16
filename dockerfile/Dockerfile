FROM ubuntu
RUN useradd foo
RUN mkdir /data &&  touch /data/file
RUN chown -R foo:foo /data
VOLUME /data
