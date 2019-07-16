# How to check env path

```powershell
dir env:path |  % {$_.Value -replace ";","`r`n"}
$env:Path.Split(";")
$env:path -split ";"
```

#### link

- https://qiita.com/kiduki/items/238e02767e90ad72b58a
