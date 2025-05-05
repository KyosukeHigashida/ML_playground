# ML_playground
機械学習について学ぶ。

## ワーキングフロー
#### 仮想環境に入る
* 初回 \
  @<project_dir>_path \
  poetry init \
  poetry install
* 仮想環境起動時 \
  @<project_dir>_path \
  source ./bin/activate (poetry shellが効かないので。)
* poetryの設定をrequirements.txtに出力 \
  poetry export -f requirements.txt --output requirements.txt4 --without-hashes
