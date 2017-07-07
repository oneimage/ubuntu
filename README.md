# oneimage

Unified Ubuntu docker images for multiple architectures.

## requirements

  * Docker Version v1.13 or later

## supported architectures

  * amd64
  * i386
  * armhf
  * arm64

## tags

  * latest
  * latest-slim
  * zesty
  * zesty-slim
  * yakkety
  * yakkety-slim
  * zesty
  * zesty-slim
  * xenial
  * xenial-slim
  * wily
  * wily-slim
  * vivid
  * vivid-slim
  * trusty
  * trusty-slim
  * precise
  * precise-slim

## running

Any hosts running the supported architectures listed above can simply run the follwing command. The correct image for your host architecture will be provided seamlessly. 

```
docker run -it oneimage/ubuntu:latest bash
```
