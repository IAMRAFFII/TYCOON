FROM souravkl11/raganork:test

RUN git clone https://github.com/Luciferking1/TYCOON/ /skl/Tycoon
WORKDIR /skl/Tycoon
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
