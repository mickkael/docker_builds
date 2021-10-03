FROM ubuntu

RUN apt update \
      && apt install -y rclone ca-certificates \
      && mkdir -p /root/.config/rclone/ \
      && rm -rf /var/lib/apt/lists/*