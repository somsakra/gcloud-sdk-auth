# GCLOUD-SDK-AUTH

## Description

File structure for using [google/cloud-sdk](https://hub.docker.com/r/google/cloud-sdk/)

---

How to run

```
docker run --rm -it --mount type=bind,source=<path-to-your-key>/config,target=/config \
--mount type=bind,source=<path-to-your-config>/configurations,target=/root/.config/gcloud/configurations \
google/cloud-sdk:alpine bash
```

How to verify

```
gcloud projects list
```
