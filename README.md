# Sublime Textの設定ファイル

## 概要
- 白雲が使用しているSublimeのパッケージ
- markdown関係とか使えそうなパッケージが入ってます
	- 詳しくは時間があったら記入する予定

## バージョン
- Sublime Text 3

## 共有のやり方
### Mac
1. [Sublime Text 3をダウンロード](https://www.sublimetext.com/3)
2. ApplicationsにSublime Textをドラッグ&ドロップ
3. ターミナルを起動
4. `cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/`
5. `git clone https://github.com/SiragumoHuin/Sublime.git .`
	- 最後に**.**をつけることで、中身だけcloneします
6. Sublime Textを起動
7. control + Shiftを押してコマンドラインを起動
8. `import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())`
	- 貼り付けてエンター。この時パッケージをインストールするので、しばらく時間がかかります。
9. 念のため再起動

### おわりに
- 各パッケージの使い方や細かな設定はググってもらえればわかるはず
- [日本語化](http://qiita.com/Shoesk/items/3e766206531dc2dcd338)
	- 上のツールバー？が所々日本語じゃないのを解消します