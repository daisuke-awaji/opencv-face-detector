# OpenCV face detector

OpenCVを使用してMacbookのインカメラを起動し、顔認識を行います。
認識された顔は白枠で囲われます。

![sample](./picture/sample.jpeg)

# Setting
事前にpython3の環境を用意して置きましょう。
python3のモジュールであるvenvを使用すると閉じたpython3環境を作ることができます。

```
$ python3 -m venv .venv
$ . .venv/bin/activate
```

以下のpip insatllによって.vnenv/lib配下にパッケージがインストールされます。

```
(.vnenv) $ pip install -r requirements.txt
```

# Run

起動方法は簡単です。
```
$ python capture.py
...<インカメラ起動>
...<終了したいときは`q`を押す>
```

