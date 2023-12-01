# 駅間の最短経路を探索するアプリケーション

### 実行するまでの手順
0. MacBookを準備します。(以降ターミナルにコピペして実行する)
1. Homebrewをインストールする。<br>
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` 
2. Python3をインストールする。<br>
`brew install python3`
3. pip3でライブラリをインストールする。<br>
`pip3 install networkx matplotlib streamlit`
4. このリポジトリをクローンする。<br>
`git clone https://github.com/elmomuds/route_search.git`
5. route_researchディレクトリに移動する。<br>
`cd route_research`
6. アプリを実行する。<br>
`streamlit run app.py`

### 導入路線
- 山手線
- 中央線
- 総武線

### バージョン
Streamlit, version 1.28.1
Python 3.11.6
