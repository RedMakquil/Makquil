FROM fusuf/whatsasena:latest
##King Makquil
RUN git clone https://github.com/RedMakquil/Makquil /root/KingMakquil
WORKDIR /root/KingMakquil/
ENV TZ=Europe/Istanbul
RUN yarn add supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
