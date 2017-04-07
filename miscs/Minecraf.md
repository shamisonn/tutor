Minecraft Modding Guide:
===
ここではMojangの作成したMOD製作において有用と考えられるオススメリンクを集約する場であります。

なお、製作に最低限の知識は以下になります。

- Javaの入門書を一冊は読んだ
- Gradle or Maven(等のビルドツール)が何となく使える
- ググる力(何気に英語が多いのでがんばる)

まず、どのMODを作る場合でも以下のリンクが役に立つのは間違いないでしょう。

- [Minecraft Modding Wiki](http://minecraftjp.info/modding/index.php/Minecraft_Modding_Wiki)

For Client(ForgeによるMOD製作)
---
とりあえず以下をメモ

- [チュートリアル一覧 - はじめに](http://minecraftjp.info/modding/index.php/%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB%E4%B8%80%E8%A6%A7#.E3.81.AF.E3.81.98.E3.82.81.E3.81.AB)

よくわからんので執筆者募集

For Server Plugin(Bukkit Plugin製作)
---
以下を上からしっかりやりましょう。
**恐らく何をやっているのかわからなくなると思うので、
自分が今何をやっているかわからない場合は、
slackの #question で聞いてください。**

- [プラグインチュートリアル](http://minecraftjp.info/modding/index.php/Plugin_Tutorial)

何をやっているかというと流れとしては

1. Mavenで外部jar(bukkit.jar)を取ってくる設定をする
1. plugin.ymlをイイカンジにいじる
1. org.bukkit.plugin.java.JavaPluginをextendsして書き始める

みたいな。

ほしい情報あったら #question にて要望ください。
