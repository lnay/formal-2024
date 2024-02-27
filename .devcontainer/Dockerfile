FROM docker.io/ubuntu:latest

RUN apt-get update && apt-get install -y build-essential git curl

ENV PATH $HOME/.elan/bin:$PATH

RUN sh -c "curl https://raw.githubusercontent.com/leanprover/elan/master/elan-init.sh -sSf > /tmp/lean.sh && chmod +x /tmp/lean.sh && /tmp/lean.sh -y"
