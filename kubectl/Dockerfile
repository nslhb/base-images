FROM arm64v8/alpine
RUN apk add --no-cache bash
ADD https://dl.k8s.io/release/v1.21.0/bin/linux/arm64/kubectl /bin
RUN chmod +x /bin/kubectl
ENTRYPOINT [ "/bin/bash" ]