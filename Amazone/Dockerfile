FROM fusuf/whatsasena:latest

RUN git clone https://github.com/En-Cuzier/Alexa-Beta /root/Alexa-Beta
WORKDIR /root/Alexa-Beta/
RUN git clone https://github.com/tenuh/Config
RUN git clone https://github.com/jesonpro/Angela-x
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
