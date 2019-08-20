FROM s5atrain/wordpress:aio
RUN apt-get update && apt-get install -y wget \
&& wget https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar \
&& mv wp-cli.phar /usr/local/bin/wp && chmod +x /usr/local/bin/wp 