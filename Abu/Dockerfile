FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Afx-Abu/Abuser /skl/Raganork
WORKDIR /skl/Raganork
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/Afx-Abu/bgms

CMD ["node", "index.js"]
