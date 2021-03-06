title: LocalStreamOptions

---

包含了音／视频开关、视频尺寸、最大帧率等选项，用于配置本地媒体流。

## 常量

### Dimension

视频分辨率选项。

**定义**

```java
	DIMENSION_120P,
	DIMENSION_240P,
	DIMENSION_360P,
	DIMENSION_480P,
	DIMENSION_720P,
	DIMENSION_1080P,
	DIMENSION_MAX;
```
### CameraSource

摄像头使用选项。

**定义**

```java
	BACK_CAMERA,
	FRONT_CAMERA;
```


## 方法

### captureVideo()

**定义**

```java
boolean captureVideo()
```

**说明**

本地视频流的视频开关,默认为开。


</br>

---

### captureAudio()

**定义**

```java
boolean captureAudio()
```

**说明**

本地视频流的音频开关,默认为开。


</br>

---

### getDimension()

**定义**

```java
Dimension getDimension()
```

**说明**

视频质量选项,默认为 `DIMENSION_480P`。

**返回值**

当前视频分辨率。

</br>

---

### getDefaultCameraSource()

**定义**

```java
CameraSource getDefaultCameraSource()
```

**说明**

摄像头使用选项，默认前置 'FRONT_CAMERA'。

**返回值**

当前使用的摄像头。

</br>

---
### getMaxFps()

**定义**

```java
int getMaxFps()
```

**说明**

传输视频的最大帧率。

**返回值**

当前视频的最大帧率的值,默认为 15fps。

</br>

---
### getMinBitrateBps()

**定义**

```java
int getMinBitrateBps()
```

**说明**

传输视频的最小码率。

**返回值**

当前视频的最小码率的值。

</br>

---

### getMaxBitrateBps()

**定义**

```java
int getMaxBitrateBps()
```

**说明**

传输视频的最大码率。

**返回值**

当前视频的最大码率的值。

</br>

---