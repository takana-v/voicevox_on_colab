# voicevox_on_colab

## PR時準備
nb-cleanを使用してメタデータを削除する。  
nb-cleanのインストールは以下の通り。  
(オリジナルのものからcolabのメタデータを削除するようにカスタマイズしている)  
```bash
pip install git+https://github.com/takana-v/nb-clean.git@60d82c2e2e2638a97f07287b837fe9129394179a
```
以下のコマンドでメタデータを削除する。
```bash
nb-clean clean VOICEVOX_on_Colab.ipynb
```
