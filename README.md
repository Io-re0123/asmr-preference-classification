# asmr-preference-classification  
音声作品の体験版から音響特徴量を作成し、好みかどうか判定するモデルを実装しました。
## 内容
Web上の音声作品をスクレイピングし体験版音声データを収集、前処理を施しアノテーションしたものからCNNモデルによる好みの分類を行いました。  
ここではスクレイピング以降のコードを掲載しています。
## 主なライブラリ
__ML__  
・[PyTorch](https://pytorch.org/ "PyTorch")  

__音声処理__  
・[Pydub](https://github.com/jiaaro/pydub "Pydub")  
・[librosa](https://librosa.org/ "librosa")  

__データ操作__  
・[NumPy](https://numpy.org/ja/ "NumPy")  
・[Pandas](https://pandas.pydata.org/ "Pandas")  

__スクレイピング__  
・[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/ "Beautiful Soup")  
