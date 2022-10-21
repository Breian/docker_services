FROM rust:1-slim-buster

ADD . /string_rust
WORKDIR /string_rust

EXPOSE 5002

RUN cargo build 

CMD ["cargo", "run"]