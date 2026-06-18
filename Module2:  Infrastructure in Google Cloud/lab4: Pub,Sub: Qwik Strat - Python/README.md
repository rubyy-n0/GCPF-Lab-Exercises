# Pub/Sub: Qwik Start - Python

## Objective

To understand how Google Cloud Pub/Sub works by creating topics, subscriptions, publishing messages, and receiving messages using Python and gcloud commands.



## Key Steps Performed

1. Checked project configuration in Cloud Shell.
2. Installed Python virtual environment and activated it.
3. Installed Google Cloud Pub/Sub Python client library.
4. Cloned the Pub/Sub sample repository.
5. Created a Pub/Sub topic named `MyTopic` using publisher script.
6. Created a subscription named `MySub` for the topic.
7. Published messages using `gcloud pubsub topics publish`.
8. Received and pulled messages using subscriber script.
9. Verified message delivery in Cloud Shell output.



## Tools / Services Used

* Google Cloud Pub/Sub
* Cloud Shell
* gcloud CLI
* Python 3
* Pub/Sub Python Client Library
* Virtual Environment (venv)



## Results

Successfully created a Pub/Sub topic and subscription, published multiple messages, and retrieved them using a subscriber. Messages were delivered asynchronously and displayed correctly in Cloud Shell.
