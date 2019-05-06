FROM makunomark/android-base
LABEL maintainer="Mark Makuno <makunomark@gmail.com>"

ENV BUILD_TOOLS "24.0.3"
ENV TARGET_SDK "24"

# Install SDK Packages
RUN ${ANDROID_HOME}/tools/bin/sdkmanager "build-tools;${BUILD_TOOLS}" "platforms;android-${TARGET_SDK}"