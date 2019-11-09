FROM node
RUN git clone https://github.com/neveisa/RBCCPS
RUN cp -R RBCCPS/NODE_HTTP_PROXY/ .
WORKDIR NODE_HTTP_PROXY
RUN bash installreq.sh
CMD node proxy.js
