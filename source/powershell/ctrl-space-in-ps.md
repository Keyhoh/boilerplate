---
title: powershellの補完機能
date: 2019-07-02
---

## powershellの補完機能

powershellで間違えて ctrl + space を入力してしまったところ、エイリアスの補完機能があったことを知った。

例えば `whe` と打って `ctrl + space` を入力すると以下のような感じになり、`tab` で値を選択できる。

```powershell
PS C:\Users\user> whe
where         Where-Object  where.exe

Where-Object
```

ただオプションやオプションコマンドは補完されないので、まだまだ不便ではある。
