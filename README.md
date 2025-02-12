# LIDAR_LD06_python_loder
A sample code for LD06 LiDAR by LDROBOT.

![Figure_1](https://user-images.githubusercontent.com/4463168/148444710-f4115412-dc99-4215-97a4-c43e471a2a62.png)

# How to use
1. Clone this repository and change `Serial(port='/dev/ttyUSB0'...)` in main.py to your own port.
2. Run `pip install -r requirements.txt` in a venv environment.
3. Run `python main.py`.
4. Press the e key to exit.

# About LD06
Data Manual, Development Manual, SDK (ROS)
- https://www.ldrobot.com/download/en/98


# LIDAR_LD06_python_loder
LDROBOT社から販売されているLidarのLD06(LDS06)をPythonから使えるようにしてみました。このサンプルコードは取得した点群をリアルタイムにMatplotlibにて表示します。

# つかいかた
1. このリポジトリをcloneし、main.pyのSerial(port='/dev/tty.usbserial-0001'...を自身のポートに変更する。
2. venv環境などで`pip install -r requirements.txt`を実行し、モジュールをインストールする。
3. `python main.py`を実行する。
4. 終了するときにはeキーを押してください。

# LD06(LDS06)について
- LD06(LDS06)入手先 https://www.inno-maker.com/product/lidar-ld06/
- (データシート、SDKなど) http://wiki.inno-maker.com/display/HOMEPAGE/LD06

