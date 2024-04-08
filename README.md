# item_modifier-enchant_randomly
item_modifierの1項目であるenchant_randomlyのサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>概要</h3>
enchant_randomlyを指示することで、ランダムにエンチャントを付与することが出来ます。<br>
この時、全てのエンチャントから選ぶのか、指定したエンチャントの中から選ぶのかといったことを決められるため、自由度が高いです。

<h3>使い方</h3>

データパック導入後、ワールドに入ることでネザライトの剣を2つ付与されます。<br>
それを手に持った状態で以下のコマンドを実行することで、enchant_randomlyを体験することが可能です。

全てのエンチャントからランダムに選ぶ場合

```copy
/item modify entity @s weapon.mainhand sample:enchant_randomly_all
```

指定したエンチャントからランダムに選ぶ場合<br>
（本データパックの場合は、幸運か無限のエンチャントが選ばれる）

```copy
/item modify entity @s weapon.mainhand sample:enchant_randomly_selected
```

---
また、ルートテーブルに組み込む場合はlootコマンドなどを実行することで入手することが可能。

本データパックでは、以下のコマンドを実行することで、エンチャントがランダムに付与された鉄の剣を入手できる。

全てのエンチャントからランダムに選ぶ場合

```copy
/loot give @s loot sample:iron_sword-all_enchants
```

指定したエンチャントからランダムに選ぶ場合<br>
（本データパックの場合は、フレイムか水中採掘のエンチャントが選ばれる）

```copy
/loot give @s loot sample:iron_sword-selected_enchants
```
