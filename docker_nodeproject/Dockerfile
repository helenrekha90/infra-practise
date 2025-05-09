FROM node:22
COPY package.json package.json
RUN npm install
COPY index.js index.js
ENTRYPOINT ["node"]
CMD ["index.js"]
