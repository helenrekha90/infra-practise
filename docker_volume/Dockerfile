FROM node:22-alpine

COPY package.json /app

# Add build context
COPY ./ /app
WORKDIR /
RUN --mount=type=cache,id=yarn,target=/usr/local/share/.cache/yarn/v6 \

yarn install --production \