FROM node:20
WoRKDIR /app
COPY package.json .
COPY *.js .
RUN npm install
ENV DB_HOST="emysql"
CMD ["node","index.js"]