# 実行環境

```
$ python -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
$ ipython kernel install --user --name=llm-sample-env
```

# テスト

```
$ pytest --nbmake ./*/**ipynb
```
