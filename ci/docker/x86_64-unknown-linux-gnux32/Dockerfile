FROM ubuntu:19.10
RUN apt-get update
RUN apt-get install -y --no-install-recommends \
  gcc-multilib libc6-dev libcap-dev ca-certificates
ENV PATH=$PATH:/rust/bin
