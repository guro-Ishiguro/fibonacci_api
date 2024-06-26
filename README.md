<div id="top"></div>

## プロジェクトについて

フィボナッチ数列を返す API

### 構成

<pre>
.
├── .env
├── .gitignore
├── README.md
├── build.sh
├── db.sqlite3
├── fibonacci_api
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── main
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── management
│   ├── models.py
│   ├── templates
│   ├── tests # 単体テスト
│   ├── urls.py # ルーティング
│   └── views.py # ビュー
├── manage.py
├── render.yaml
└── requirements.txt
</pre>

### 環境

| 言語・フレームワーク  | バージョン |
| --------------------- | ---------- |
| Python                | 3.11.4     |
| Django                | 5.0.1      |
| Django Rest Framework | 3.15.1     |

### ローカルでのプロジェクトの作成と起動

```bash
git clone https://github.com/guro-Ishiguro/fib_api.git
cd fibonacci_api
pip install -r requirements.txt
python3 manage.py runserver
```

### 動作確認

以下の URL にアクセスする<br>
https://fibonacci-api-jozr.onrender.com/fib?n=100<br>
