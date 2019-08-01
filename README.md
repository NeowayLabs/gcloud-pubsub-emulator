# Google Cloud PubSub Emulator Docker
This is the Docker image for the [Google Cloud PubSub Emulator](https://cloud.google.com/sdk/gcloud/reference/beta/emulators/pubsub/)

## Usage
To run it you can use

    docker run --rm -p "8085:8085" .../gcloud-pubsub-emulator

> Notice the usage of the `PUBSUB_EMULATOR_HOST` to let the pubsub client know about the emulator.