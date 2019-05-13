FROM twigatech/android-alpine-base
LABEL maintainer="Twiga Tech <eng@twigafoods.com>"

ENV BUILD_TOOLS "22.0.1"
ENV TARGET_SDK "22"

# Install SDK Packages
RUN ${ANDROID_HOME}/tools/bin/sdkmanager "build-tools;${BUILD_TOOLS}" "platforms;android-${TARGET_SDK}"