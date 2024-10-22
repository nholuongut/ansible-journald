# Ansible role to enforce configuration of a journald log system
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

# Quickstart
Just have a systemd-journald instance installed, set up the variables defined
in defaults/main.yml as you wish and include the role.
```
- name: configure journald
  hosts: all
  roles: stone-payments.journald
```
# Configs
The defaults provided here are the same of a EL7.4 default distribution.
```
journald_storage_option: "auto"
journald_compress_option: "yes"
journald_seal_option: "yes"
journald_splitmode: "uid"
journald_sync_interval: "5m"
journald_rate_limit_interval: "30s"
journald_rate_limit_burst: "1000"
journald_system_max_use: ""
journald_system_keep_free: ""
journald_max_file_size: ""
journald_runtime_max_use: ""
journald_runtime_keep_free: ""
journald_runtime_max_file_size: ""
journald_max_retention_sec: ""
journald_max_file_sec: "1month"
journald_forward_to_syslog: "yes"
journald_forward_to_kmsg: "no"
journald_forward_to_console: "no"
journald_forward_to_wall: "yes"
journald_tty_path: "/dev/console"
journald_max_level_store: "debug"
journald_max_level_syslog: "debug"
journald_max_level_kmsg: "notice"
journald_max_level_console: "info"
journald_max_level_wall: "emerg"

```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
