FROM fusuf/whatsasena:latest

RUN git clonehttps://github.com/Sanjayponnu/Amal/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
