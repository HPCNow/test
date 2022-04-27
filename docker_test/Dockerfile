FROM XXXX

# Install packages dependencies
RUN dnf -y update && \
    dnf clean all && \
    dnf -y install epel-release && \
    dnf -y install dnf-plugins-core && \
    dnf config-manager --set-enabled powertools && \
    dnf -y install \
        unzip \
        bzip2 \
        patch \
        mlocate \
        tcl \
        tcl-devel \
        Lmod \
        lua \
        lua-json \
        lua-lpeg \
        lua-term \
        lua-filesystem \
        lua-posix \
        python3 \
        python3-pip \
        libibverbs-devel \
        which && \
     XXXX

