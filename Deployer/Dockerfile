FROM cjsewell/silverstripe-web-yarn:latest

ENV PATH="/root/.composer/vendor/bin:${PATH}"
ENV COMPOSER_ALLOW_SUPERUSER=1
RUN apt-get -yq update && apt-get install -yq rsync
RUN composer global require --no-ansi --prefer-dist --optimize-autoloader deployer/deployer:^6.1
