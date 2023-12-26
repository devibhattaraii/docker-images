FROM ghcr.io/cirruslabs/flutter:3.16.5

WORKDIR /app

RUN apt-get update && \
  apt-get install -y --no-install-recommends ca-certificates \
  wget cmake ninja-build clang build-essential pkg-config libgtk-3-dev && \
  update-ca-certificates

RUN apt-get install openjdk-11-jre -y

RUN update-java-alternatives --set /usr/lib/jvm/java-1.11.0-openjdk-amd64


CMD ["sleep", "infinity"]