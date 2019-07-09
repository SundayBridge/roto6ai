Orange Pi Zeroを使ってWordPressが動くWebサーバを立ち上げる(2019/7)
========================

[roto6ai]を公開するに当たって、買ったまま放置していた[Orange Pi Zero]を使って
Webサーバを立ち上げたので、設定方法をまとめておく

使用したもの
-------------------
1. [Orange Pi Zero] 本体(今回はメモリが512MBを使用)
2. USB Micro Type-Bケーブルと充電器（スマホによく使うやつ。2.4Aだとなおよし）
3. Sundisk MicroSD 16GB A1(容量は4GBでも十分。OSのArmbianはA1やA2規格を推奨環境としている)


構成
-------------------



That's it.  Pretty simple.  There's also a drop-down option in the upper right to switch between various views:

- **Preview:**  A live display of the generated HTML as it would render in a browser.
- **HTML Source:**  The generated HTML before your browser makes it pretty.
- **Lexer Data:**  What [marked] uses internally, in case you like gory stuff like this.
- **Quick Reference:**  A brief run-down of how to format things using markdown.

Why Markdown?
-------------

It's easy.  It's not overly bloated, unlike HTML.  Also, as the creator of [markdown] says,

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

Ready to start writing?  Either start changing stuff on the left or
[clear everything](/demo/?text=) with a simple click.

[Marked]: https://github.com/markedjs/marked/
[Markdown]: http://daringfireball.net/projects/markdown/
[roto6ai]: https://roto6ai.0am.jp/
[Orange Pi Zero]: http://www.orangepi.org/orangepizero/
