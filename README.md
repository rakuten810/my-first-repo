# my-first-repo
# pip install mecab
# pip install unidic-lite
import pandas as pd
import MeCab
# build tagger object
mecab = MeCab.Tagger() 
text = "黒島区長の川井さんは、修復に携わった人々への感謝とともに「神輿が帰ってきて町に元気が出て、祭りにたくさんの人が来ると期待しています」と思いを語りました。"
result = mecab.parse(text)
print(result)
