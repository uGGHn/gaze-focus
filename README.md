# 注视对焦 gaze-focus

手机网页原型：前置摄像头估计视线，照片以注视点为中心由清晰到模糊。

- 在线打开：https://ugghn.github.io/gaze-focus/
- A 径向：以注视点为圆心向外模糊
- B 景深：对焦到注视物体的距离，前后景模糊

眼动识别使用 Google MediaPipe Face Landmarker（Apache-2.0），文件放在 `mp/` 目录，便于国内网络加载。
