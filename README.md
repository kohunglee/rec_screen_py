# rec_screen_py
使用Python来录屏（类似延时摄影、快镜头那种）（原理就是每个几秒截一下屏，然后最后再合成一个视频）

![image](https://github.com/kohunglee/rec_screen_py/assets/33373536/9ed7986e-35d1-4376-b6ae-251178a5a55b)

看起来就是这个样子。

运行的话，可能需要一些第三方库吧，cv2 这个，我也不晓得，试试呗。只需要：

```shell
pip3 install opencv-python
或
pip install opencv-python
```

然后就是运行：

```shell
python3 main.py
```

其中进入后要写项目名，支持中文，就是你次录像是干啥的，比如：“用 PS 画一个山水画”

然后点击开始录制，目前是大约五六秒截一张图片（这个好难调，因为 Python 这个时间不太准），之后你就干你的事就行了。（图会截到你目录下的一个新建文件夹里，文件夹名称就是你的项目名）

结束了点结束，然后点抓换视频，你可以在目录下的 `video_output` 里看到结果视频，体积可能有点大，但没办法。

这便是全部了。
