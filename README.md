# hakkason0920
"""
#環境
動作確認プラットフォーム：Streamlit Cloud
利用言語：Python3.11.9
フレームワーク：streamlit
認証：Google Cloud サービスアカウントを利用
ライブラリ：google-auth,gspread,google-auth-oauthlib

推奨環境：
    VSCode → 1.90以上
    Google Chrome　→　latest ver.

目的：日付、場所、時間の希望を募る
    例）大学祭の施設利用の希望調査
    ＊注意このとき入力の重複を許すため”予約”とは異なる


使用感フロー：
　場所、日付、時間の設定をする
    ↓
　URLを公開
    ↓
　利用者が第3希望まで入力
    ↓
　パスワードを知っている人のみ管理者画面に移行
    ↓
　Excelファイルですべての希望を出力・確認できる
　　
