# Publish
$ curl -d "topic=some-topic-name&message=This is my message." http://www.cactusmq.com/publish/${CACTUSMQ_PUBKEY};

# Subscribe
$ curl -N http://www.cactusmq.com/subscribe/${CACTUSMQ_SUBKEY};
