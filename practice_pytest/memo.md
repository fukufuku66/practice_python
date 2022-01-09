# pytest使ってみた
### pytestで使えるテスト用コードのファイル名  
* test_*.py  
* *_test.py


### 書き方

assertに条件式を指定し、期待値と実際の結果が一致するかどうかを検証する

```python:基本の書き方
def test_1():
    "実行結果" = ○○関数()
    assert "期待値" == "実行結果"
```

### 実行方法
コンソールでpytestコマンドを実行する
```console:コンソール
C:\Users\user>pytest
```