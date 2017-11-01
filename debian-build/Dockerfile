ARG CHROME_VERSION=latest
FROM yukinying/chrome-headless:${CHROME_VERSION}

# build rootfs
RUN rm -f chrome/Dockerfile
RUN mkdir chrome/locales
ADD locales/en-US.pak chrome/locales
RUN tar cf /chrome.tar chrome
RUN cd /usr/lib/x86_64-linux-gnu && tar cf /nss.tar nss