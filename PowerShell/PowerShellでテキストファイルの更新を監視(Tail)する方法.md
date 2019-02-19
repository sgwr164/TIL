# PowerShellでテキストファイルの更新を監視(Tail)する方法

以下のコマンドレットで、テキストファイルの更新を監視できる。

```powershell
Get-Content foo.txt -Tail 0 -Wait

# エイリアス
type foo.txt -Tail 0 -Wait
```

## Reference

[windowsでもリアルタイムでログ監視(tail -f)がしたい！](https://qiita.com/rache/items/7ebde61df17f193d79de)

