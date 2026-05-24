# Eikana (⌘英かな)
Apple Silicon ready: this build runs natively on M1/M2/M3/M4 Macs and remains compatible with Intel Macs as a Universal 2 app.

This application switches alphanumeric / kana when pushing left and right command keys.
It can also be used as a key remapping application that works even with macOS Sierra by fiddling with settings in the preferences window.

## Download
Download the Apple Silicon compatible Universal 2 release from the GitHub Pages site:
https://shierote.github.io/cmd-eikana-apple-silicon/

## Build from source
Release archives are configured as Universal 2 binaries (`arm64` + `x86_64`) for native Apple Silicon support and Intel Mac compatibility.

## How to use (at first launch)
⌘ Open the .app. Since it is unsigned, please open it by right clicking and choosing "Open".
The app will display a confirmation dialog for accessibility functions, click on "Open" System Preferences ". Please click on the key in the lower left to unlock and mark ⌘ (Eikana) app as checked.

## How to Quit
Open the "⌘" icon in the status bar at the top right and select "Quit".

## How to uninstall

⌘ Drag app to the trash
Also, the configuration file is located at ~ / Library / Preferences / io.github.imasanari.cmd - eikana.plist. If you want to erase cleanly please also put this in the garbage can.

## Tested for compatibility with
- OS X El Capitan 10.11.5 (未確認)
- Mac OS Sierra 10.12 (未確認)
- macOS Big Sur 11.1 (Apple M1)

## License
MIT License


# ⌘英かな
Apple Silicon対応版です。M1/M2/M3/M4 Macでネイティブ動作し、Intel Macにも対応する Universal 2 アプリとして配布しています。

左右のコマンドキーを単体で押した時に英数/かなを切り替えるようにするアプリです。  
設定をいじることでmacOS Sierraでも動くキーリマップアプリとしても利用できます。  

## ダウンロード
Apple Silicon対応の Universal 2 版を GitHub Pages の配布ページからダウンロードしてください。

https://shierote.github.io/cmd-eikana-apple-silicon/

## ソースからビルド
Release の Archive は Apple Silicon ネイティブ対応 / Intel Mac 互換の Universal 2 バイナリ（`arm64` + `x86_64`）としてビルドされる設定です。

## 使い方（初回起動時）

eikana.appを起動させます。未署名ですので[右クリック操作](https://support.apple.com/ja-jp/HT202491)で開いてください。

アクセシビリティ機能へのアクセスの確認ダイアログが表示されるので「"システム環境設定"を開く」をクリックします。
左下の鍵をクリックして解除し、eikana.appにチェックを入れてください。

## 終了方法

右上のステータスバーにある「⌘」アイコンを開き、「Quit」を選びます。

## アンインストール方法

eikana.appをゴミ箱に入れてください。

また、設定ファイルが`~/Library/Preferences/io.github.imasanari.cmd-eikana.plist`にあります。
綺麗さっぱり消したいという場合はこちらもゴミ箱に入れてください。

## 動作確認

- OS X El Capitan 10.11.5 (未確認)
- mac OS Sierra 10.12 (未確認)
- macOS Big Sur 11.1 (Apple M1)

## ライセンス
MIT License
