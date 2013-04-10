# HIPHOP系プログラミング言語 ﾁｪｹﾗｰ
ﾖｰﾁｪｹﾗｯﾁｮｰ!

## 言語仕様
| 命令 | 意味 |
|---:|:---|
| COME ON! | ポインタを１進める |
| HO! | ポインタを１戻す |
| YO! | ポインタの指す値を１増やす |
| WOW! | ポインタの指す値を１減らす |
| ﾁｪｹﾗｰ! | ポインタの指す値が０なら、対応する```YEAH!```までジャンプする |
| YEAH! | ポインタの指す値が０でないなら、対応する```ﾁｪｹﾗｰ!```までジャンプする |
| AHA!? | ポインタの指す値を出力する |
| SO COOL! | 入力から１バイト読み込む |

## サンプル
### hello.yo
> COME ON!YO!YO!YO!YO!YO!YO!YO!YO!YO!ﾁｪｹﾗｰ!HO!YO!YO!YO!YO!YO!YO!YO!YO!COME ON!WOW!YEAH!HO!AHA!?COME ON!YO!YO!YO!YO!YO!YO!YO!ﾁｪｹﾗｰ!HO!YO!YO!YO!YO!COME ON!WOW!YEAH!HO!YO!AHA!?YO!YO!YO!YO!YO!YO!YO!AHA!?AHA!?YO!YO!YO!AHA!?ﾁｪｹﾗｰ!WOW!YEAH!COME ON!YO!YO!YO!YO!YO!YO!YO!YO!ﾁｪｹﾗｰ!HO!YO!YO!YO!YO!COME ON!WOW!YEAH!HO!AHA!?COME ON!YO!YO!YO!YO!YO!YO!YO!YO!YO!YO!YO!ﾁｪｹﾗｰ!HO!YO!YO!YO!YO!YO!COME ON!WOW!YEAH!HO!AHA!?COME ON!YO!YO!YO!YO!YO!YO!YO!YO!ﾁｪｹﾗｰ!HO!YO!YO!YO!COME ON!WOW!YEAH!HO!AHA!?YO!YO!YO!AHA!?WOW!WOW!WOW!WOW!WOW!WOW!AHA!?WOW!WOW!WOW!WOW!WOW!WOW!WOW!WOW!AHA!?ﾁｪｹﾗｰ!WOW!YEAH!COME ON!YO!YO!YO!YO!YO!YO!YO!YO!ﾁｪｹﾗｰ!HO!YO!YO!YO!YO!COME ON!WOW!YEAH!HO!YO!AHA!?ﾁｪｹﾗｰ!WOW!YEAH!YO!YO!YO!YO!YO!YO!YO!YO!YO!YO!AHA!?

### 実行
```
$ ./checkitout hello.yo
Hello World!
```

## 参考
- [The Brainfuck Programming Language](http://www.muppetlabs.com/~breadbox/bf/)
- [masarakki/r-fxxk - Github](https://github.com/masarakki/r-fxxk)