FROM nyholm/roave-bc-check:base
MAINTAINER Tobias Nyholm <tobias.nyholm@gmail.com>

ENV BC_CHECK_VERSION 6.x

RUN composer global require --no-update "roave/backward-compatibility-check:^6.0" \
    && composer global update \
    && composer global show | grep backward-compatibility-check
