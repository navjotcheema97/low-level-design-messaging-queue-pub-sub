# Low Level System Design - PubSub Messaging Queue

### Problem statement
[Check here](problem-statement.md)

### Project requirements
* JDK 1.8
* Maven

## APIs supported in queue
* createTopic(topicName) -> topicId
* subscribe(topicId, subscriber) -> boolean
* publish(topicId, message) -> boolean
* readOffset(topidId, subscriber, offset) -> boolean
