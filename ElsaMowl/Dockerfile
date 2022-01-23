FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Abhiraj/MR-PO /root/WhatsAsenaDuplicated

WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Abhiraj90/Media

CMD ["node", "bot.js"]
