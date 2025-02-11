# Basic Information of Selected Projects

| Project       | Size (KLOC) | Description                                                |
|---------------|-------------|------------------------------------------------------------|
| act           | 17          | GitHub local execution tool                                |
| AdGuardHome   | 43          | Privacy protection center                                  |
| alist         | 40          | File listing program supporting multiple storage backends |
| caddy         | 44          | Cross-platform web server                                  |
| clash         | 21          | Rule-based network tunneling tool                          |
| Cloudreve     | 42          | Cloud storage system supporting multiple cloud providers   |
| compose       | 20          | Tool for running multi-container applications              |
| croc          | 4           | Lightweight file transfer tool                             |
| GoFrame       | 172         | Modular development framework                              |
| gitea         | 259         | Self-hosted Git service platform                           |
| gost          | 23          | Network security tunneling tool                            |
| photoprism    | 141         | AI-powered photo software                                  |
| rclone        | 210         | Tool for syncing cloud files                               |
| v2ray         | 89          | Network protocol platform                                  |

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
