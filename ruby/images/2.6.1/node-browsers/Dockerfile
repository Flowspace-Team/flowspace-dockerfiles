FROM circleci/ruby:2.6.1-node-browsers

RUN sudo apt-get update

RUN sudo apt-get install -y libsodium-dev

RUN sudo apt-get install -y postgresql-client

# Add imagemagick- and PDF-related packages
RUN sudo apt-get install -y build-essential git curl cmake xvfb libfontconfig wkhtmltopdf imagemagick
