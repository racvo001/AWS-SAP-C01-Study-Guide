# Using SNS with AWS Architecture

* [Return to table of contents](../../../README.md)

* **Useful Links:**
  * [Common Amazon SNS Scenarios](https://docs.aws.amazon.com/sns/latest/dg/sns-common-scenarios.html)

* **Exam Tips:**
  * Notification system - Not queueing.
  * If there needs to be messages sent, default to SNS in the exam.
  * Replicated and durable - Regional.
  * **Topic:**
    * Object where you publish your message (<= 256 KB>)
  * **Subscriber:**
    * Endpoint where the message is sent.
    * Available endpoints:
      * HTTP/S
      * Email(JSON)
      * SQS
      * Mobile
      * Lambda
      * SMS
  * **Publisher:**
    * The entitiy that triggets the sending of a message.
  * **Fanout:**
    * Allows a SNS message to be replicated and pushed to multiple SQS queues.
