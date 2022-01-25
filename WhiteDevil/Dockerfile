FROM KTBwhitedevil:latest

RUN git clone https://github.com/MJMODS/BlackGod /root/whitedevil
WORKDIR /root/whitedevil/ 
ENV KL=Kerala/India
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/MJMODS/BlackGod

CMD ["node","white", "bot.js"]
