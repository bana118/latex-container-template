FROM debian:buster-slim

# Reference https://texwiki.texjp.org/?Linux%2FLinux%20Mint#texlive
# texlive full package (Install if latex does not work properly)
# texlive-full

RUN apt update \
    && apt install -y --no-install-recommends \
    apt-utils \
    git \
    texlive-lang-japanese \
    texlive-lang-english \
    texlive-luatex \
    texlive-latex-recommended \
    texlive-latex-extra \
    fonts-lmodern \
    texlive-xetex \
    latex-cjk-common \
    texlive-fonts-recommended \
    texlive-fonts-extra \
    texlive-extra-utils \
    latexmk \
    liblog-log4perl-perl \
    libyaml-tiny-perl \
    libfile-homedir-perl \
    liblog-dispatch-perl \
    && apt autoremove -y \
    && apt clean -y \
    && rm -rf /var/lib/apt/lists/*
