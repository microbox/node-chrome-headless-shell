FROM yukinying/chrome-headless:62.0.3201.2

# build rootfs
RUN tar cf /chrome.tar chrome
RUN cd /usr/lib/x86_64-linux-gnu && tar cf /nss.tar nss