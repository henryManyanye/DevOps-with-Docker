FROM node:15.4-alpine3.10

EXPOSE 5000

WORKDIR /usr/src/app

COPY . .

RUN <<EOF
npm install
npm run build
npm install -g serve
EOF

CMD serve -s -l 5000 build



