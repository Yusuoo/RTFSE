<a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


![GitHub Logo](https://github.com/Yusuoo/RTFSE/blob/master/OperatingSystem(OS)/images/CK20160626273814_TP_V4.jpg)

# インストール方法

試しにCentOS7.3をインストールしてみる。

* 用意するもの 
  * OSが何も入ってない。もしくは入ってるけど消して良いPC
    （仮想化技術使うと楽ですが、今回はCentOS用のPCを作成する想定）
  * DVD
  * 手順2までを作業する別PC
  
* 手順
  * 1.CentOS7.3のISOをイメージを[サイト*1](http://ftp.iij.ad.jp/pub/linux/centos/7/isos/x86_64/CentOS-7-x86_64-Minimal-1810.iso)よりダウンロードする
  * 2.ダウンロードしたイメージをDVDに焼く
  * 3.DVDをPCに挿入し、電源をOn
  * 4.CentOS7のインストール画面が表示されるので"Install CentOS Linux 7"を選択した状態でENTER
  * 5."日本語"を押下して、続行
  * 6."パーティションを自分で構成する"を押下
  * 7.完了を押下
  * 8."変更を許可する"を押下
  * 9."ネットワークとホスト名"を押下
  * 10.右上のボタンを押下して"オン"状態にする
  * 11."完了"を押下
  * 12."インストールの開始"を押下
  * 13."ROOTパスワード"を押下
  * 14.rootパスワードに好きなパスワードを2箇所入力し、"完了"ボタンを２回押下
  * 15."再起動"を押下
  * 16.再起動が完了したあと、root/14のPW でログインする
  
  
*1：常にサイトは最新になっていくので、リンク切れの場合は[ここ](http://ftp.iij.ad.jp/pub/linux/centos/7/isos/x86_64/)にアクセスし、CentOS-7-x86_64-Minimal-***を取得
