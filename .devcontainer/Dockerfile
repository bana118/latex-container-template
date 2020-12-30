FROM debian:buster-slim

# Reference https://texwiki.texjp.org/?Linux%2FLinux%20Mint#texlive
# If you use only Japanese fonts
# use the following packages instead of tex-live-full to save space
    # texlive-lang-japanese \
    # texlive-luatex \
    # texlive-latex-recommended \
    # texlive-latex-extra \
    # fonts-lmodern \
    # texlive-xetex \
    # latex-cjk-common \
    # texlive-fonts-extra \
    # texlive-extra-utils \
    # latexmk \
RUN apt update \
    && apt install -y --no-install-recommends \
    apt-utils \
    git \
    texlive-full \
    liblog-log4perl-perl \
    libyaml-tiny-perl \
    libfile-homedir-perl \
    liblog-dispatch-perl \
    && apt autoremove -y \
    && apt clean -y \
    && rm -rf /var/lib/apt/lists/*
