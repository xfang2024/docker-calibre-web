<!-- DO NOT EDIT THIS FILE MANUALLY -->
<!-- Please read https://github.com/linuxserver/docker-calibre-web/blob/master/.github/CONTRIBUTING.md -->
[![linuxserver.io](https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/linuxserver_medium.png)](https://linuxserver.io)

[![Blog](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Blog)](https://blog.linuxserver.io "all the things you can do with our containers including How-To guides, opinions and much more!")
[![Discord](https://img.shields.io/discord/354974912613449730.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Discord&logo=discord)](https://discord.gg/YWrKVTn "realtime support / chat with the community and the team.")
[![Discourse](https://img.shields.io/discourse/https/discourse.linuxserver.io/topics.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=discourse)](https://discourse.linuxserver.io "post on our community forum.")
[![Fleet](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Fleet)](https://fleet.linuxserver.io "an online web interface which displays all of our maintained images.")
[![GitHub](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub&logo=github)](https://github.com/linuxserver "view the source for all of our repositories.")
[![Open Collective](https://img.shields.io/opencollective/all/linuxserver.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Supporters&logo=open%20collective)](https://opencollective.com/linuxserver "please consider helping us by either donating or contributing to our budget")

The [LinuxServer.io](https://linuxserver.io) team brings you another container release featuring:

* regular and timely application updates
* easy user mappings (PGID, PUID)
* custom base image with s6 overlay
* weekly base OS updates with common layers across the entire LinuxServer.io ecosystem to minimise space usage, down time and bandwidth
* regular security updates

Find us at:

* [Blog](https://blog.linuxserver.io) - all the things you can do with our containers including How-To guides, opinions and much more!
* [Discord](https://discord.gg/YWrKVTn) - realtime support / chat with the community and the team.
* [Discourse](https://discourse.linuxserver.io) - post on our community forum.
* [Fleet](https://fleet.linuxserver.io) - an online web interface which displays all of our maintained images.
* [GitHub](https://github.com/linuxserver) - view the source for all of our repositories.
* [Open Collective](https://opencollective.com/linuxserver) - please consider helping us by either donating or contributing to our budget

# [linuxserver/calibre-web](https://github.com/linuxserver/docker-calibre-web)

[![Scarf.io pulls](https://scarf.sh/installs-badge/linuxserver-ci/linuxserver%2Fcalibre-web?color=94398d&label-color=555555&logo-color=ffffff&style=for-the-badge&package-type=docker)](https://scarf.sh)
[![GitHub Stars](https://img.shields.io/github/stars/linuxserver/docker-calibre-web.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-calibre-web)
[![GitHub Release](https://img.shields.io/github/release/linuxserver/docker-calibre-web.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-calibre-web/releases)
[![GitHub Package Repository](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub%20Package&logo=github)](https://github.com/linuxserver/docker-calibre-web/packages)
[![GitLab Container Registry](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitLab%20Registry&logo=gitlab)](https://gitlab.com/linuxserver.io/docker-calibre-web/container_registry)
[![Quay.io](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Quay.io)](https://quay.io/repository/linuxserver.io/calibre-web)
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/calibre-web.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=pulls&logo=docker)](https://hub.docker.com/r/linuxserver/calibre-web)
[![Docker Stars](https://img.shields.io/docker/stars/linuxserver/calibre-web.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=stars&logo=docker)](https://hub.docker.com/r/linuxserver/calibre-web)
[![Jenkins Build](https://img.shields.io/jenkins/build?labelColor=555555&logoColor=ffffff&style=for-the-badge&jobUrl=https%3A%2F%2Fci.linuxserver.io%2Fjob%2FDocker-Pipeline-Builders%2Fjob%2Fdocker-calibre-web%2Fjob%2Fmaster%2F&logo=jenkins)](https://ci.linuxserver.io/job/Docker-Pipeline-Builders/job/docker-calibre-web/job/master/)
[![LSIO CI](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=CI&query=CI&url=https%3A%2F%2Fci-tests.linuxserver.io%2Flinuxserver%2Fcalibre-web%2Flatest%2Fci-status.yml)](https://ci-tests.linuxserver.io/linuxserver/calibre-web/latest/index.html)

[Calibre-web](https://github.com/janeczku/calibre-web) is a web app providing a clean interface for browsing, reading and downloading eBooks using an existing Calibre database.   It is also possible to integrate google drive and edit metadata and your calibre library through the app itself.

This software is a fork of library and licensed under the GPL v3 License.

[![calibre-web](https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/calibre-web-icon.png)](https://github.com/janeczku/calibre-web)

## Supported Architectures

We utilise the docker manifest for multi-platform awareness. More information is available from docker [here](https://distribution.github.io/distribution/spec/manifest-v2-2/#manifest-list) and our announcement [here](https://blog.linuxserver.io/2019/02/21/the-lsio-pipeline-project/).

Simply pulling `lscr.io/linuxserver/calibre-web:latest` should retrieve the correct image for your arch, but you can also pull specific arch images via tags.

The architectures supported by this image are:

| Architecture | Available | Tag |
| :----: | :----: | ---- |
| x86-64 | ✅ | amd64-\<version tag\> |
| arm64 | ✅ | arm64v8-\<version tag\> |
| armhf | ❌ | |

## Version Tags

This image provides various versions that are available via tags. Please read the descriptions carefully and exercise caution when using unstable or development tags.

| Tag | Available | Description |
| :----: | :----: |--- |
| latest | ✅ | Releases of Calibre-Web |
| nightly | ✅ | Commits to the master branch of Calibre-Web |

## Application Setup

Webui can be found at `http://your-ip:8083`

On the initial setup screen, enter `/books` as your calibre library location.

**Default admin login:**
*Username:* admin
*Password:* admin123

If you lock yourself out or forget a password, you will need to specify the app.db similar to this: 
`docker exec -it calibre-web python3 /app/calibre-web/cps.py -p /config/app.db -s <user>:<pass>`
If you fail to specify the proper db, it will appear to succeed, but it will not work.

Unrar is included by default and needs to be set in the Calibre-Web admin page (Basic Configuration:External Binaries) with a path of `/usr/bin/unrar`

**64bit only** We have implemented the optional ability to pull in the dependencies to enable ebook conversion utilising Calibre, this means if you don't require this feature the container isn't uneccessarily bloated but should you require it, it is easily available.
This optional layer will be rebuilt automatically on our CI pipeline upon new Calibre releases so you can stay up to date.
To use this option add the optional environmental variable as shown in the docker-mods section to pull an addition docker layer to enable ebook conversion and then in the Calibre-Web admin page (Basic Configuration:External Binaries) set the **Path to Calibre E-Book Converter** to `/usr/bin/ebook-convert`

This image contains the [kepubify](https://pgaskin.net/kepubify/) ebook conversion tool (MIT License) to convert epub to kepub.  In the Calibre-Web admin page (Basic Configuration:External Binaries) set the **Path to Kepubify E-Book Converter** to `/usr/bin/kepubify`

## Usage

To help you get started creating a container from this image you can either use docker-compose or the docker cli.

### docker-compose (recommended, [click here for more info](https://docs.linuxserver.io/general/docker-compose))

```yaml
---
services:
  calibre-web:
    image: lscr.io/linuxserver/calibre-web:latest
    container_name: calibre-web
    environment:
      - PUID=1000
      - PGID=1000
      - TZ=Etc/UTC
      - DOCKER_MODS=linuxserver/mods:universal-calibre #optional
      - OAUTHLIB_RELAX_TOKEN_SCOPE=1 #optional
    volumes:
      - /path/to/data:/config
      - /path/to/calibre/library:/books
    ports:
      - 8083:8083
    restart: unless-stopped
```

### docker cli ([click here for more info](https://docs.docker.com/engine/reference/commandline/cli/))

```bash
docker run -d \
  --name=calibre-web \
  -e PUID=1000 \
  -e PGID=1000 \
  -e TZ=Etc/UTC \
  -e DOCKER_MODS=linuxserver/mods:universal-calibre `#optional` \
  -e OAUTHLIB_RELAX_TOKEN_SCOPE=1 `#optional` \
  -p 8083:8083 \
  -v /path/to/data:/config \
  -v /path/to/calibre/library:/books \
  --restart unless-stopped \
  lscr.io/linuxserver/calibre-web:latest
```

## Parameters

Containers are configured using parameters passed at runtime (such as those above). These parameters are separated by a colon and indicate `<external>:<internal>` respectively. For example, `-p 8080:80` would expose port `80` from inside the container to be accessible from the host's IP on port `8080` outside the container.

| Parameter | Function |
| :----: | --- |
| `-p 8083` | WebUI |
| `-e PUID=1000` | for UserID - see below for explanation |
| `-e PGID=1000` | for GroupID - see below for explanation |
| `-e TZ=Etc/UTC` | specify a timezone to use, see this [list](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones#List). |
| `-e DOCKER_MODS=linuxserver/mods:universal-calibre` | #optional & **x86-64 only** Adds the ability to perform ebook conversion |
| `-e OAUTHLIB_RELAX_TOKEN_SCOPE=1` | Optionally set this to allow Google OAUTH to work |
| `-v /config` | Where calibre-web stores the internal database and config. |
| `-v /books` | Where your preexisting calibre database is located. |

## Environment variables from files (Docker secrets)

You can set any environment variable from a file by using a special prepend `FILE__`.

As an example:

```bash
-e FILE__MYVAR=/run/secrets/mysecretvariable
```

Will set the environment variable `MYVAR` based on the contents of the `/run/secrets/mysecretvariable` file.

## Umask for running applications

For all of our images we provide the ability to override the default umask settings for services started within the containers using the optional `-e UMASK=022` setting.
Keep in mind umask is not chmod it subtracts from permissions based on it's value it does not add. Please read up [here](https://en.wikipedia.org/wiki/Umask) before asking for support.

## User / Group Identifiers

When using volumes (`-v` flags), permissions issues can arise between the host OS and the container, we avoid this issue by allowing you to specify the user `PUID` and group `PGID`.

Ensure any volume directories on the host are owned by the same user you specify and any permissions issues will vanish like magic.

In this instance `PUID=1000` and `PGID=1000`, to find yours use `id your_user` as below:

```bash
id your_user
```

Example output:

```text
uid=1000(your_user) gid=1000(your_user) groups=1000(your_user)
```

## Docker Mods

[![Docker Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=calibre-web&query=%24.mods%5B%27calibre-web%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=calibre-web "view available mods for this container.") [![Docker Universal Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=universal&query=%24.mods%5B%27universal%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=universal "view available universal mods.")

We publish various [Docker Mods](https://github.com/linuxserver/docker-mods) to enable additional functionality within the containers. The list of Mods available for this image (if any) as well as universal mods that can be applied to any one of our images can be accessed via the dynamic badges above.

## Support Info

* Shell access whilst the container is running:

    ```bash
    docker exec -it calibre-web /bin/bash
    ```

* To monitor the logs of the container in realtime:

    ```bash
    docker logs -f calibre-web
    ```

* Container version number:

    ```bash
    docker inspect -f '{{ index .Config.Labels "build_version" }}' calibre-web
    ```

* Image version number:

    ```bash
    docker inspect -f '{{ index .Config.Labels "build_version" }}' lscr.io/linuxserver/calibre-web:latest
    ```

## Updating Info

Most of our images are static, versioned, and require an image update and container recreation to update the app inside. With some exceptions (noted in the relevant readme.md), we do not recommend or support updating apps inside the container. Please consult the [Application Setup](#application-setup) section above to see if it is recommended for the image.

Below are the instructions for updating containers:

### Via Docker Compose

* Update images:
    * All images:

        ```bash
        docker-compose pull
        ```

    * Single image:

        ```bash
        docker-compose pull calibre-web
        ```

* Update containers:
    * All containers:

        ```bash
        docker-compose up -d
        ```

    * Single container:

        ```bash
        docker-compose up -d calibre-web
        ```

* You can also remove the old dangling images:

    ```bash
    docker image prune
    ```

### Via Docker Run

* Update the image:

    ```bash
    docker pull lscr.io/linuxserver/calibre-web:latest
    ```

* Stop the running container:

    ```bash
    docker stop calibre-web
    ```

* Delete the container:

    ```bash
    docker rm calibre-web
    ```

* Recreate a new container with the same docker run parameters as instructed above (if mapped correctly to a host folder, your `/config` folder and settings will be preserved)
* You can also remove the old dangling images:

    ```bash
    docker image prune
    ```

### Image Update Notifications - Diun (Docker Image Update Notifier)

**tip**: We recommend [Diun](https://crazymax.dev/diun/) for update notifications. Other tools that automatically update containers unattended are not recommended or supported.

## Building locally

If you want to make local modifications to these images for development purposes or just to customize the logic:

```bash
git clone https://github.com/linuxserver/docker-calibre-web.git
cd docker-calibre-web
docker build \
  --no-cache \
  --pull \
  -t lscr.io/linuxserver/calibre-web:latest .
```

The ARM variants can be built on x86_64 hardware using `multiarch/qemu-user-static`

```bash
docker run --rm --privileged multiarch/qemu-user-static:register --reset
```

Once registered you can define the dockerfile to use with `-f Dockerfile.aarch64`.

## Versions

* **17.10.23:** - Remove some packages that are required by the calibre mod but not the base container.
* **07.10.23:** - Install unrar from [linuxserver repo](https://github.com/linuxserver/docker-unrar). Switch to Python virtual environment.
* **13.04.23:** - Deprecate armhf.
* **27.03.23:** - Add cmake as build dep for Levenshtein.
* **27.12.22:** - Add ghostscript, libxtst6, libxkbfile-dev.
* **20.12.22:** - Improve init script and prevent harmless error.
* **19.10.22:** - Rebase to jammy. Upgrade to s6v3. Clean up build dependencies.
* **04.11.21:** - Update pip arguments to ignore distro installed packages.
* **24.06.21:** - Add note on optional OAUTHLIB_RELAX_TOKEN_SCOPE for Google OAUTH support.
* **17.05.21:** - Add linuxserver wheel index.
* **10.02.21:** - Add libxrandr2
* **25.01.21:** - Add nightly tag
* **19.01.21:** - Add python3-pkg-resources
* **13.01.21:** - Rebase to Ubuntu Focal, see [here](https://docs.linuxserver.io/faq#my-host-is-incompatible-with-images-based-on-ubuntu-focal) for troubleshooting armhf.
* **12.10.20:** - Add libxi6
* **12.07.20:** - Add kepubify for arm64v8
* **05.06.20:** - Add kepubify for x86-64 and arm32v7
* **06.05.20:** - Add libxslt1.1 and update ImageMagick policy
* **19.01.20:** - Adding LDAP libs.
* **13.10.19:** - Migrate to Python3.
* **01.08.19:** - Add libxcomposite1.
* **13.06.19:** - Add docker mod to enable optional ebook conversion on x86-64.  Add unrar.
* **02.06.19:** - Rebase to Ubuntu Bionic & add Gdrive support.
* **23.03.19:** - Switching to new Base images, shift to arm32v7 tag.
* **23.02.19:** - Rebase to alpine 3.9, use repo version of imagemagick.
* **11.02.19:** - Add pipeline logic and multi arch.
* **03.01.19:** - Remove guest user from default app.db.
* **16.08.18:** - Rebase to alpine 3.8.
* **03.07.18:** - New build pushed, all versions below `67` have [vulnerability](https://github.com/janeczku/calibre-web/issues/534).
* **05.01.18:** - Deprecate cpu_core routine lack of scaling.
* **06.12.17:** - Rebase to alpine 3.7.
* **27.11.17:** - Use cpu core counting routine to speed up build time.
* **24.07.17:** - Curl version for imagemagick.
* **17.07.17:** - Initial release.
