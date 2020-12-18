FROM debian:buster-slim

# Reference https://texwiki.texjp.org/?Linux%2FLinux%20Mint#texlive
# Full texlive package is texlive-full
RUN apt update \
    && apt install -y --no-install-recommends \
    apt-utils \
    git \
    texlive-lang-japanese \
    texlive-luatex \
    texlive-latex-recommended \
    texlive-latex-extra \
    fonts-lmodern \
    texlive-xetex \
    latex-cjk-common \
    texlive-fonts-extra \
    texlive-extra-utils \
    latexmk \
    && apt autoremove -y \
    && apt clean -y \
    && rm -rf /var/lib/apt/lists/*
