FROM circleci/buildpack-deps

RUN curl https://cli-assets.heroku.com/install.sh | sh

RUN mkdir ~/.ssh
RUN echo "VerifyHostKeyDNS yes\n" >> ~/.ssh/config
RUN echo "StrictHostKeyChecking no\n" >> ~/.ssh/config
