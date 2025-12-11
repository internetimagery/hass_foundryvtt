# https://developers.home-assistant.io/docs/add-ons/configuration#add-on-dockerfile
ARG BUILD_FROM
FROM $BUILD_FROM

# Install dependencies
RUN apk add --no-cache nodejs

# Copy root filesystem
COPY rootfs /

