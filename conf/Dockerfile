# Dockerfile

# Ubuntu 20.04をベースにする
FROM ubuntu:20.04

# キーボードの選択で停止しないように
ENV DEBIAN_FRONTEND=noninteractive

# X Window Systemをインストールする
RUN apt-get update && apt-get install -y x11-xserver-utils xorg

# xeyesパッケージをインストールする
RUN apt-get update && apt-get install -y x11-apps

CMD ["/bin/bash"]
