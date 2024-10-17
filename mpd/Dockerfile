ARG BUILD_FROM
ARG TARGETOS
ARG TARGETARCH
FROM $BUILD_FROM

RUN apk add --no-cache \
        mpc=0.35-r0 \
        mpd=0.23.15-r2 \
        ympd=1.3.0-r12

ENTRYPOINT [ "/init" ]
CMD []
COPY root /
