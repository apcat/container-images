ARG CLOUD_SDK_VERSION
FROM gcr.io/google.com/cloudsdktool/cloud-sdk:${CLOUD_SDK_VERSION}-emulators

CMD ["beta", "emulators", "pubsub", "start", "--host-port=0.0.0.0:8085"]
EXPOSE 8085
