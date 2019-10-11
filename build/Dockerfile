FROM alpine:3.10

ADD message.txt /volume/message.txt

CMD while sleep 1; do echo "$(date): $(cat volume/message.txt)"; done
