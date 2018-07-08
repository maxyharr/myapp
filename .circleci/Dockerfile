FROM node:8.11.3
# For using newest npm version as well
# And having access to angular cli directly
RUN npm install -g npm @angular/cli

# Install chrome for running tests
RUN wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
RUN dpkg -i google-chrome-stable_current_amd64.deb; apt-get -fy install
