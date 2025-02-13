# Basic Information of Selected Projects

| Project       | Size (KLOC) | Description                                                | Link
|---------------|-------------|------------------------------------------------------------|--------------------------------------|
| act           | 17          | GitHub local execution tool                                | [act](https://github.com/nektos/act) |
| AdGuardHome   | 43          | Privacy protection center                                  | [AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) |
| alist         | 40          | File listing program supporting multiple storage backends  | [alist](https://github.com/alist-org/alist) | 
| caddy         | 44          | Cross-platform web server                                  | [caddy](https://github.com/caddyserver/caddy) |
| clash         | 21          | Rule-based network tunneling tool                          | [clash](https://github.com/Dreamacro/clash) |
| Cloudreve     | 42          | Cloud storage system supporting multiple cloud providers   | [Cloudreve](https://github.com/cloudreve/Cloudreve) |
| compose       | 20          | Tool for running multi-container applications              | [compose](https://github.com/docker/compose) |
| croc          | 4           | Lightweight file transfer tool                             | [croc](https://github.com/schollz/croc) |
| GoFrame       | 172         | Modular development framework                              | [GoFrame](https://github.com/gogf/gf) |
| gitea         | 259         | Self-hosted Git service platform                           | [gitea](https://github.com/go-gitea/gitea) |
| gost          | 23          | Network security tunneling tool                            | [gost](https://github.com/ginuerzh/gost) |
| photoprism    | 141         | AI-powered photo software                                  | [photoprism](https://github.com/photoprism/photoprism) |
| rclone        | 210         | Tool for syncing cloud files                               | [rclone](https://github.com/rclone/rclone) |
| v2ray         | 89          | Network protocol platform                                  | [v2ray](https://github.com/v2fly/v2ray-core) |

# Real project defect reports that have been confirmed by developers

| Project Name | Location                                                                                  | Fixed | Defect Report Link                                        |
|--------------|-------------------------------------------------------------------------------------------|-------|-----------------------------------------------------------|
| act <br> commit id: 816a7d      |   act/cmd/root.go:651 <br> act/cmd/root.go:666                        | √     | [#1741](https://github.com/nektos/act/issues/1741)          |
| act <br> commit id: 816a7d      |   act/cmd/root.go:657 <br> act/cmd/root.go:666                        | √     | [#1741](https://github.com/nektos/act/issues/1741)          |
| croc <br> commit id: 3c1d60d    |   croc/src/croc/croc.go:573 <br> croc/src/croc/croc.go:638           | x     | [#567](https://github.com/schollz/croc/issues/567)         |
| gitea <br> commit id: dad057b   |   gitea/services/migrations/gitea_uploader.go:869 <br> gitea/services/migrations/gitea_uploader.go:880 | √     | Email report                                              |
| gitea <br> commit id: dad057b   |   gitea/services/migrations/gitea_uploader.go:869 <br> gitea/services/migrations/gitea_uploader.go:878 | √     | Email report                                              |
| gitea <br> commit id: dad057b   |   gitea/modules/markup/renderer.go:236 <br> gitea/modules/markup/renderer.go:247 | x     | Email report                                              |
| gitea <br> commit id: dad057b   |   gitea/modules/markup/renderer.go:236 <br> gitea/modules/markup/renderer.go:249 | x     | Email report                                              |
| rclone <br> commit id: 927e72   |   rclone/vfs/read.go:234 <br> rclone/vfs/read.go:241                 | √     | [#6962](https://github.com/rclone/rclone/issues/6962)       |
| rclone <br> commit id: 927e72   |   rclone/cmd/serve/dlna/dlna.go:306 <br> rclone/cmd/serve/dlna/dlna.go:312 | √     | [#6962](https://github.com/rclone/rclone/issues/6962)       |
| rclone <br> commit id: 927e72   |   rclone/cmd/serve/dlna/dlna.go:307 <br> rclone/cmd/serve/dlna/dlna.go:312 | √     | [#6962](https://github.com/rclone/rclone/issues/6962)       |
| rclone <br> commit id: 927e72   |   rclone/cmd/serve/dlna/dlna.go:308 <br> rclone/cmd/serve/dlna/dlna.go:312 | √     | [#6962](https://github.com/rclone/rclone/issues/6962)       |
