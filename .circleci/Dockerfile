FROM circleci/node:8.11.3-browsers

RUN mkdir ~/.npm-global
RUN npm config set prefix '~/.npm-global'
RUN export PATH=~/.npm-global/bin:$PATH
# For using newest npm version as well
# And having access to angular cli directly
RUN npm install -g npm @angular/cli

RUN export CHROME_BIN=/usr/bin/google-chrome
