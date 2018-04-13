# はじめに

これは、Karabiner-Elements用設定ファイルです。
Microsoft Remote Desktop利用時のみ、JISキーボードをUSキーボードにマッピングします。

通常、RemoteDesktopを使うと、自分のキーボードの設定にかかわらず、USキーボードとして認識されてしまいます。
この設定ファイルを利用し、Karabiner-Elements上でComplex Modifications上で有効にすると、RemoteDesktopアプリ利用時のみ、JISキーボードで入力した文字コードをUSキーボードの対応する文字コードに変換してくれます。

# 使い方

rdp-custom-keyboard.jsonファイルを、~/.config/karabiner/assets/complex_modifications の下にコピーします。

すると、Karabiner-Elementsを実行したときに、Complex Modificationsタブを開き、「Add rule」ボタンを押すと
「RDPCustom keyboard」というセクションが表示されていると思います。
そこにある、「JIS to US with backslash」をEnableにすれば有効になります。

使うのをやめるときは「JIS to US with backslash」をRemoveにすれば無効になります。

削除するときは、~/.config/karabiner/assets/complex_modificationsから、rdp-custom-keyboard.jsonを削除してください。
