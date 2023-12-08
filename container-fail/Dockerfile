FROM vulnerables/web-dvwa
COPY secret.yaml /secret.yaml
RUN mkdir -p /home/se/.aws/
COPY awssecret.txt /home/se/.aws/credentials
