# mikutterが起動するなにか
(C) 2013 gofer (@gofer_ex).

## 使い方
<ol>
<li><p>
mikutterを落としてきて/usr/localとかに展開する
<code><pre>
$ wget http://mikutter.hachune.net/bin/mikutter.0.2.2.1373.tar.gz
$ mv ./mikutter.0.2.2.1373.tar.gz /usr/local
$ tar xvf /usr/local/mikutter.0.2.2.1373
$ rm -f /usr/local/mikutter.0.2.2.1373.tar.gz
</pre></code>
</p></li>

<li><p>
この怪しげなブツを/usr/binとかに置く
<code><pre>
$ git clone https://github.com/gofer/mikutter_run.git
$ sudo mv ./mikutter_run/mikutter /usr/bin
$ rm -rf ./mikutter_run
</pre></code>
</p></li>

<li><p>
空気を読んで
<code><pre>
$ chmod +x /usr/bin/mikutter
</pre></code>
とかする
</p></li>

<li><p>
これでいつでも
<code><pre>
$ mikutter
</pre></code>
でておくれになれる
</p></li>
</ol>
