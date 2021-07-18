FROM fusuf/whatsasena:latest

RUN git close https://github.com/Noobmaster200/Sophia/root/WatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
