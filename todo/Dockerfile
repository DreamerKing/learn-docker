FROM node
MAINTAINER dreamingking@live.cn
RUN git clone -q https://github.com/DreamerKing/learn-server.git todo
WORKDIR todo
RUN npm install > /dev/null
# RUN npm install pm2 -g
EXPOSE 3000
CMD ["npm", "start"]