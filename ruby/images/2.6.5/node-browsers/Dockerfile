FROM circleci/ruby:2.6.5-node-browsers

RUN sudo apt-get update

RUN sudo apt-get install -y libsodium-dev

RUN sudo apt-get install -y postgresql-client

# Add imagemagick
RUN sudo apt-get install -y build-essential git curl cmake xvfb libfontconfig imagemagick

# wkhtmltopdf
RUN sudo apt-get install -y xfonts-75dpi
RUN sudo wget https://github.com/wkhtmltopdf/wkhtmltopdf/releases/download/0.12.5/wkhtmltox_0.12.5-1.buster_amd64.deb
RUN sudo dpkg -i wkhtmltox_0.12.5-1.buster_amd64.deb
