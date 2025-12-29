FROM teddysun/xray:latest
COPY config.json /etc/xray/config.json
USER root
EXPOSE 7860
CMD ["xray", "-config", "/etc/xray/config.json"]
