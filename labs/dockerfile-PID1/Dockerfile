FROM nginx

RUN apt-get update && apt-get install -y procps && rm -rf /var/lib/apt/lists/*

COPY start.sh /start.sh
RUN chmod 755 /start.sh

#CMD "/start.sh"
CMD ["/start.sh"]
