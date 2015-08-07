FROM node
RUN npm install express
RUN npm install redis
ADD files/ /files/
COPY webui.js /
CMD ["node", "webui.js"]
