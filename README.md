# aruco_ros
arReader for ROS
# 導入手順
## arucoライブラリをインストール
以下のURLからaaruco-2.0.19.zipをダウンロード　※バージョンは都度変更する可能性あり

https://sourceforge.net/projects/aruco/files/2.0.19/

任意のダウンロード先で以下のコマンドを実行してインストール
```
cd Downloads/aruco-2.0.14
mkdir build
cd build
cmake ..
make
sudo make install 
```

## aruco_rosをgitから取得し、makeする
```
cd ~/catkin_ws/src  
git clone https://github.com/shashankvkt/aruco_ros  
cd ..  
catkin_make --pkg ros_aruco -DARUCO_PATH=/usr/local  
```

# 実行手順
## カメラを起動

## aruco_rosを実行
