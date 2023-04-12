# 프로그램 설치

1. Chocolatey

윈도우에서 사용하는 brew 같은 도구. 이번에 처음 알았다.

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

2. fnm (Fast Node Manager)

실행이 안되면, 내가 shell setup을 했는지 떠올려보자... 20분 헤맴🤦‍♀️

```bash
fnm env --use-on-cd | Out-String | Invoke-Expression
```
