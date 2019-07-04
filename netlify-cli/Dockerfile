FROM node:10-alpine
LABEL MAINTAINER Siritas Dho <siritas@gmail.com>

ENV NPM_CONFIG_PREFIX=/home/node/.npm-global
ENV PATH=$PATH:/home/node/.npm-global/bin 

RUN npm install netlify-cli -g

USER node