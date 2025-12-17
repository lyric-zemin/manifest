# manifest

# env
- [nvs](https://github.com/jasongin/nvs) - node版本管理
- [cz-git](https://cz-git.qbb.sh/zh/cli/install) - git命令式提交
- [ni](https://github.com/antfu-collective/ni) - 自动包管理识别
- [degit](https://github.com/Rich-Harris/degit) - 仓库脚手架

<br/>

# cli
- [cli自动补全](https://juejin.cn/post/7187442172671557689)
- [Oh My Posh](https://ohmyposh.dev/docs/installation/windows) - powershell美化

<details>
  <summary>Microsoft.PowerShell_profile配置</summary>

  ```ps1
  # Shows navigable menu of all options when hitting Tab
  Set-PSReadlineKeyHandler -Key Tab -Function MenuComplete

  # Autocompletion for arrow keys
  Set-PSReadlineKeyHandler -Key UpArrow -Function HistorySearchBackward
  Set-PSReadlineKeyHandler -Key DownArrow -Function HistorySearchForward

  # auto suggestions
  Import-Module PSReadLine
  Set-PSReadLineOption -PredictionSource History

  # oh-my-posh主题
  oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\json.omp.json" | Invoke-Expression

  # Conflicts with ni
  Remove-Item Alias:ni -Force -ErrorAction Ignore
  ```
</details>

<br/>

# client
- PowerToys - Windows工具集
- Xshell - sh客户端
- EV录屏 - 录屏软件
- Expo Orbit - 模拟客户端管理调试
- v2rayN - 代理客户端
- PicGo - 个人图片管理
- VMware Workstation Pro - 虚拟机

<details>
  <summary>v2rayN订阅地址</summary>

  ```
  https://gh-proxy.com/raw.githubusercontent.com/ssrsub/ssr/master/v2ray

  https://gh-proxy.com/raw.githubusercontent.com/bin1site1/V2rayFree/refs/heads/main/config.txt

  https://raw.githubusercontent.com/free-nodes/v2rayfree/main/v2
  ```
</details>

