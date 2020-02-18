FROM rust:1.41.0-slim
RUN apt-get update -yqq && apt-get install -yqq curl && rm -rf /var/lib/apt/lists/* 
RUN curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
