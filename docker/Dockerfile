FROM nginx


# Switch to directory with sources
WORKDIR /src


# # Copy required stuff
# COPY . .

EXPOSE 80

# RUN yarn global add serve

# CMD ["serve", "-s", "build"]

COPY ./nginx/nginx.conf /etc/nginx/conf.d/default.conf
COPY  . /usr/share/nginx/html
