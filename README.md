# StreemShell

The command line shell for data processing

## Usage

```sh
➜  streemshell git:(master) ✗ cat bigdata.log
hoge
hige
moge
➜  streemshell git:(master) ✗ ./streemshell
-> cat bigdata.log | map { l -> "hello, " + l } | echo
hello, hoge
hello, hige
hello, moge
```

## Co-Author

- [@mpon](https://github.com/mpon)