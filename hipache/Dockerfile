FROM komljen/nodejs
MAINTAINER Alen Komljen <alen.komljen@live.com>

RUN npm install hipache -g

ADD config.json config.json
ADD start.sh start.sh

EXPOSE 80
RUN rm /usr/sbin/policy-rc.d
CMD ["/start.sh"]
