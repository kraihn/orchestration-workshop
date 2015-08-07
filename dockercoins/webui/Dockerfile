FROM node
RUN npm install express
RUN npm install redis
RUN git clone https://github.com/jpetazzo/orchestration-workshop.git /orchestration
RUN mkdir files
COPY files/ /files/
COPY webui.js /
CMD ["node", "webui.js"]
