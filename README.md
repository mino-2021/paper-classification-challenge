# paper-classification-challenge
paper-classification-challenge, https://signate.jp/competitions/471 / 医学論文の自動仕分けチャレンジ

■関連技術

自然言語処理　BERT 文書分類 pytorch BERT huggingface 

LB 4位

PB 35位

■取り組みの工夫

BERT分類モデルの改良(max pooling+mean pooling追加)

Automatic Mixed Precision (AMP)：PyTorchでの学習を高速化

不均衡データのため損失関数の重み付け実施

