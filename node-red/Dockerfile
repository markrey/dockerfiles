FROM node:0.12

MAINTAINER cpswan

# install node-red
RUN npm install -g node-red
RUN npm install -g node-red-contrib-parallel-iterator
RUN npm install -g node-red-contrib-flow-combine
RUN npm install -g node-red-contrib-input-split

# expose port
EXPOSE 1880

# Set the default command to execute
# when creating a new container
CMD ["/usr/local/bin/node-red"]
