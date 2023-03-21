Scratch では、条件が真になるたびにコード ブロックを実行すると便利なことがよくあります。

これを行うには、 `もし...なら`{:class="block3control"} ブロックを `ずっと`{:class="block3control"} ブロック内に配置します。 たとえば、`フラグが押されたとき`{:class="block3events"} や、`メッセージを受け取ったとき`{:class="block3events"} ブロックなどでスクリプトを起動する必要があります。

ゲーム内で重要な条件を確認できます。

```blocks3
forever
if <touching color (#6a4200) ?> then
say [Nooooo!] for [2] seconds
go to (Start v)
end
end
```

または、 `変数`{:class="block3variables"} 値で `演算子`{:class="block3operators"} を使用することを確認してください。

```blocks3
forever
if <(health) < [5]> then
say [Warning! Low health] for [2] seconds
end
end
```
