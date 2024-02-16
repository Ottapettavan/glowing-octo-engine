cost = ottapettavan 

RUN git  https://github.com/Ottapettavan/SHAH-MWOL
WORKDIR / SHAH-MWOL 
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ottapettavan/media

CMD ["node", "bot.js"]
