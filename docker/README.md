# Docker存储文件夹|Docker Storage Folder

其中一些容器需要更多的步骤来安装或者构建，**所以最好先学习一下docker的基础知识**，然后再来参照使用。

欢迎提出建议和问题。

Some of them will ask for more steps to install or build, so that it is better for you to learn docker basic knowledge to read and use them.

Welcome for your advice and issue.

---
## 通用信息|General Information

* 由于本人网络环境问题，与多stack导致的巨多网段的问题，所以在`docker-compose.yml`中，所有的`network_mode`都被设置为`bridge`，并且**应该**都被我注释掉了，如果你的网络环境没有问题，可以自行修改。
* 部分`docker-compose.yml`中的`docker.env`推荐重命名为`.docker.env`的格式，这样可以避免一些不必要的问题，但是本人由于不想让文件隐藏，所以没有这么做。
* 列表中的绝大多数都是我现在正在使用的服务，绝大多数都是对比过同类产品后的较优选择。

==============================

* Due to the problem of my network environment and the huge number of network segments caused by multiple stacks, in `docker-compose.yml`, all `network_mode` are set to `bridge`, and **should** be commented out by me. If your network environment is fine, you can modify it yourself.
* Some `docker.env` in `docker-compose.yml` are recommended to be renamed to `.docker.env` format, which can avoid some unnecessary problems, but I don't want to hide the file, so I didn't do it.
* Most of the services in the list are the ones I am currently using, and most of them are the better choice after comparing with the same products. 
---
## 目录|Catalog
* [dashy](dashy/) | [Source Code](https://github.com/Lissy93/dashy), [Official Website](https://dashy.to/)

    可以直接在WEB界面编辑的Dashboard，可以方便的管理多个网站并进行导航。
    
    A self-hostable personal dashboard built for you. Includes status-checking, widgets, themes, icon packs, a UI editor and tons more!

* [databases](databases/)

    一些常用的数据库，包括MySQL,PostgreSQL,Redis。
    
    Some common databases, including MySQL, PostgreSQL, Redis.
    
* [derper](derper/) | [Source Code](https://github.com/tailscale/tailscale), [Official Website](https://tailscale.com/)
    
    Tailscale的中继服务器，用于提升境内的访问速度和可用性。
    
    Tailscale relay server, used to improve the speed and availability of domestic access.

* [dns](dns/) | [Source Code](https://github.com/TechnitiumSoftware/DnsServer), [Official Website](https://technitium.com/dns/)
    
    WEB界面的DNS服务器，可以方便的管理DNS记录。
    
    A DNS server with a web interface that can be used to manage DNS records.

* [gitlab](gitlab/) | [Source Code](gitlab/README.md), [Official Website](https://about.gitlab.com/)
    
    Gitlab-EE的Crack镜像，只需生成对应的证书文件即可享受企业版全功能订阅。
    
    Gitlab-EE Crack image, just generate the corresponding certificate file to enjoy the full function subscription of the enterprise version.

* [headscale](headscale/) | [Source Code](https://github.com/juanfont/headscale)
    
    Tailscale的开源版服务器，由第三方社区维护。
    
    Tailscale open source server, maintained by the third-party community.

* [jsoncrack](jsoncrack/) | [Source Code](https://github.com/0x727/ShuiZe_0x727)
    
    jsoncrack的Docker镜像，用于解析JSON文件。
    
    jsoncrack Docker image, used to parse JSON files.

* [keycloak](keycloak/) | [Source Code](https://github.com/keycloak/keycloak), [Official Website](https://www.keycloak.org/)
    
    OIDC服务器，支持SAML,LDAP,OAuth2等认证方式，具有WEB界面和丰富的功能，可以实现多种需求。
    
    An open source OIDC server, supporting SAML, LDAP, OAuth2 and other authentication methods, with a WEB interface and rich features, can achieve a variety of needs.
    
* [memos](memos/) | [Source Code](https://github.com/usememos/memos), [Official Website](https://usememos.com/)
    
    每日随手笔记，类似微博，个人版，可以快速形成当日记录。
    
    An open source daily casual note, similar to Weibo, personal version, can quickly form daily records.

* [minecraft](minecraft/) | [Source Code](https://github.com/itzg/docker-minecraft-server)
    
    我的世界服务器Docker版本，作者做了 [JE](https://github.com/itzg/docker-minecraft-server) 和 [BE](https://hub.docker.com/r/itzg/minecraft-bedrock-server) 两个版本，可以根据自己的需求选择。
    
    Minecraft Server Docker version, the author made two versions [JE](https://github.com/itzg/docker-minecraft-server) and [BE](https://hub.docker.com/r/itzg/minecraft-bedrock-server), you can choose according to your needs.

* [minio](minio/) | [Source Code](https://github.com/minio/minio), [Official Website](https://min.io/)
    
    AWS S3兼容服务，可以作为本地搭建的AWS S3或COS服务器。
    
    An open source AWS S3 compatible service, can be used as a local AWS S3 or COS server.

* [n8n](n8n/) | [Source Code](https://github.com/n8n-io/n8n), [Official Website](https://n8n.io/)
    
    工作流引擎，可以通过可视化的方式实现各种自动化任务，功能强大。
    
    An open source workflow engine that can achieve various automation tasks through visualized ways, and it's powerful.

* [nextcloud](nextcloud/) | [Source Code](https://github.com/nextcloud/docker), [Official Website](https://nextcloud.com/)
    
    免费开源私有云，功能相对丰富，可以实现文件同步，日历，通讯录，在线即时聊天等功能。但是代码效率相对有些低，相对而言其优势在于具有大量的社区插件可以提供更加丰富的功能。

    Free open source private cloud, relatively rich in features, can achieve file synchronization, calendar, address book, online instant messaging and other functions. But the code efficiency is relatively low, and the advantage is that it has a large number of community plug-ins that can provide more rich functions.

* [nginx-proxy-manager](nginxproxymanager/) | [Source Code](https://github.com/NginxProxyManager/nginx-proxy-manager), [Official Website](https://nginxproxymanager.com/)
    
    WEB界面的Nginx反向代理管理器，可以方便的管理多个反向代理。
    
    A WEB interface Nginx reverse proxy manager, which can easily manage multiple reverse proxies.

* [outline](outline/) | [Source Code](https://github.com/outline/outline), [Official Website]()
    
    团队协作Wiki，搭建相对复杂，但是具有较为现代的界面和完善的功能。
    
    An open source team collaboration Wiki, which is relatively complex to build, but has a more modern interface and complete functions.

* [plex](plex/) | [Source Code](https://github.com/plexinc/pms-docker), [Official Website](https://www.plex.tv/)
    
    Plex是一个多媒体管理系统，可以实现多个设备之间的同步，支持多种格式的视频，音乐，图片等。
    
    Plex is a multimedia management system that can achieve synchronization between multiple devices, and supports various formats of video, music, pictures, etc.

* [shuize](shuize/) | [Source Code](https://github.com/0x727/ShuiZe_0x727), [Official Website]()
    
    水泽，由0x727团队信息收集自动化工具。
    
    Shuize, an information collection automation tool open sourced by the 0x727 team.

* [speedtest](speedtest/) | [Source Code](https://github.com/librespeed/speedtest), [Official Website](https://librespeed.org/)
    
    Speedtest工具，可以测试上传和下载速度。
    
    An open source Speedtest tool that can test upload and download speeds.

* [stash](stash/) | [Source Code](https://github.com/librespeed/speedtest), [Official Website](https://stashapp.cc/)
    
    R18影片管理工具，不过作为媒体库管理软件，功能还是十分强大的，不一定只能用来存R18，用于标记、分类、查重其他各类媒体文件也是不错的选择。
    
    R18 video management tool, but as a media library management software, the function is still very powerful, not necessarily only to store R18, to mark, classify, duplicate other types of media files is also a good choice.

* [synapse](synapse/) | [Source Code](https://github.com/matrix-org/synapse), [Official Website](https://matrix-org.github.io/synapse)
    
    Synapse：用 Python/Twisted 编写的 Matrix 家庭服务器。可用于自建Matrix服务器。
    
    Synapse: Matrix homeserver written in Python/Twisted. Can be used to build a Matrix server.

* [syncthing](syncthing/) | [Source Code](https://github.com/syncthing/syncthing), [Official Website](https://syncthing.net/)
    
    文件同步工具，可以实现多台设备之间的跨平台文件同步。
    
    File synchronization tool that can achieve cross-platform file synchronization between multiple devices.

* [tachidesk](tachidesk/) | [Source Code](https://github.com/Suwayomi/Tachidesk-Server)
    
    Tachidesk是一个开源的Manga阅读器，可以实现Manga的在线阅读，下载，管理等功能，属于Tachiyomi的一个第三方开源重构版本，可以通过插件与Tachiyomi联动。
    
    Tachidesk is an open source Manga reader that can achieve online reading, download, management and other functions of Manga, which is a third-party open source reconstruction version of Tachiyomi. It can be linked with Tachiyomi through plug-ins.

* [teamspeak](teamspeak/) | [Official Website](https://www.teamspeak.com/)
    
    语音聊天工具，可以实现多人语音聊天，支持多种平台。免费版本最多支持30人同时连接到同一服务器，付费版本可以支持更多人同时连接。
    
    Voice chat tool that can achieve multi-person voice chat, and supports multiple platforms. The free version supports up to 30 people connecting to the same server at the same time, and the paid version can support more people connecting at the same time.

* [uptime-kuma](uptime-kuma/) | [Source Code](https://github.com/louislam/uptime-kuma), [Official Website](https://louislam.net/uptime-kuma/)
    
    服务监控工具，用于检查指定的服务/端口是否在正常运行或证书是否即将过期，内嵌了多种通知方式。
    
    A service monitoring tool for checking whether a specified service/port is running normally or whether a certificate is about to expire, with multiple built-in notification methods.

* [vaultwarden](vaultwarden/) | [Source Code](https://github.com/dani-garcia/vaultwarden), [Official Website](https://vaultwarden.net/)
    
    密码管理器Bitwarden的第三方开源服务器，借助官方的客户端和浏览器插件就可以实现Bitwarden的全功能。
    A third-party open-source server for password manager Bitwarden can be used to access all of Bitwarden's features through the official client and browser plugin.

* [wallabag](wallabag/) | [Source Code](https://github.com/wallabag/wallabag), [Official Website](https://www.wallabag.org/)
    
    用于保存和分类网页的开源工具，可以保存为多种格式，同时支持RSS，可以在RSS客户端上直接进行阅读。
    
    An open source tool for saving and classifying web pages, which can be saved in multiple formats and supports RSS, which can be read directly on RSS clients.

* [watchtower](watchtower/) | [Source Code](https://github.com/containrrr/watchtower), [Official Website](https://containrrr.dev/watchtower/)
    
    自动更新Docker容器的工具，可以自动检测并更新Docker容器。
    
    A tool for automatically updating Docker containers, which can automatically detect and update Docker containers.

* [yourls](yourls/) | [Source Code](https://github.com/YOURLS/YOURLS), [Official Website](https://yourls.org/)
    
    开源可自建的短网址服务，支持自定义后缀，搭建快速，无需设置。
    
    An open source self-build short URL service, which supports custom suffixes, is quick to build, and does not need to be set.