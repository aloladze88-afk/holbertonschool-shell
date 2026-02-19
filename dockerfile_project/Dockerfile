FROM alpine:3.19
WORKDIR /app
COPY message.txt /app/message.txt
RUN apk add --no-cache curl wget
CMD ["cat", "/app/message.txt"]
