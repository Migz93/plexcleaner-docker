Check https://github.com/jorenn92/Maintainerr for an alternative.

# plexcleaner-docker
[![Docker Image CI](https://github.com/Migz93/plexcleaner-docker/actions/workflows/main.yml/badge.svg)](https://github.com/Migz93/plexcleaner-docker/actions/workflows/main.yml)  
Updated to use python3 as the original docker container was breaking on some special characters.

# Docker Command
```bash
docker run -d \
  --name plexcleaner \
  -v /path/to/config:/config \
  -v /path/to/logs:/logs \
  -v /path/to/media:/path/to/media/as/seen/by/plex \
  -e EXECUTION_CRON_EXPRESSION="0 * * * *" \
  miguel1993/plexcleaner-docker
```

# Versions
* 30/08/2022 - Update workflow, update readme, rename branch.  
* 09/10/2021 - Rename repository.  
* 11/09/2021 - Initial release.  

# Credits
Forked from https://github.com/Chuppa/docker-plexcleaner  
Script is https://github.com/ngovil21/Plex-Cleaner  

# Notes
I no longer use this so cannot confirm it still works.

