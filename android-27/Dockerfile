FROM makunomark/android-base
LABEL maintainer="Mark Makuno <makunomark@gmail.com>"

ENV BUILD_TOOLS "27.0.3"
ENV TARGET_SDK "27"

# Install SDK Packages
RUN ${ANDROID_HOME}/tools/bin/sdkmanager "build-tools;${BUILD_TOOLS}" "platforms;android-${TARGET_SDK}"