FROM fusuf/whatsasena:latest

RUN git clone https://Sew01RaviduManoj01KingAndQueen:queensew1@github.com/Sew01RaviduManoj01KingAndQueen/QueenSewSL /root/QueenSewSL
WORKDIR /root/QueenSewSL/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
