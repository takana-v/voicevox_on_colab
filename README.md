# voicevox_on_colab

## PR時準備
nb-cleanを使用してメタデータを削除する。  
nb-cleanのインストールは以下の通り。  
(オリジナルのものからcolabのメタデータを削除するようにカスタマイズしている)  
```bash
pip install git+https://github.com/takana-v/nb-clean.git@455ecc6e145196c97a54f7adeb4e0cb950a34e68
```
以下のコマンドでメタデータを削除する。
```bash
nb-clean clean VOICEVOX_on_Colab.ipynb
```
