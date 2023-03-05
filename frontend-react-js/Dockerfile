FROM node:19-alpine

COPY . .

WORKDIR /frontend-react-js

# Install dependencies
RUN npm install

ENV PORT=3001
EXPOSE 3001

CMD [ "npm", "start" ]
