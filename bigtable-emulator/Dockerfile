ARG CLOUD_SDK_VERSION
FROM gcr.io/google.com/cloudsdktool/cloud-sdk:${CLOUD_SDK_VERSION}-emulators

CMD ["beta", "emulators", "bigtable", "start", "--host-port=0.0.0.0:8086"]
EXPOSE 8086
