FROM twigatech/android-alpine-base
LABEL maintainer="Twiga Tech <eng@twigafoods.com>"

ENV BUILD_TOOLS "23.0.3"
ENV TARGET_SDK "23"

# Install SDK Packages
RUN ${ANDROID_HOME}/tools/bin/sdkmanager "build-tools;${BUILD_TOOLS}" "platforms;android-${TARGET_SDK}"