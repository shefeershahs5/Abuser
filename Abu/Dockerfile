FROM abu/abuser:latest

RUN git clone https://github.com/Afx-Abu/Abuser /abu/Abuser
WORKDIR /abu/Abuser
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/Afx-Abu/bgms

CMD ["node", "Abu.js"]
