FROM scratch
LABEL org.label-schema.vendor="Blitznote" \
      org.label-schema.build-date="2016-11-02T18:53:52+00:00" \
      org.label-schema.name="minimal base images with Ubuntu" \
      org.label-schema.vcs-type="git" \
      org.label-schema.vcs-url="https://github.com/Blitznote/docker-ubuntu-debootstrap"

ADD rootfs.tar.xz /
CMD ["/bin/bash"]
SHELL ["/bin/bash", "-c"]
