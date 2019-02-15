FROM cjsewell/silverstripe-web-yarn

RUN apt-get -yq update && apt-get install -yq rsync
RUN  composer global require --no-ansi --prefer-dist --optimize-autoloader deployer/deployer:^6.1