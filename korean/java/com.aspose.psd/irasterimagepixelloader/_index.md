---
title: "IRasterImagePixelLoader"
second_title: "Java용 Aspose.PSD API 참조"
description: "래스터 이미지 픽셀 로더."
type: docs
weight: 136
url: /ko/java/com.aspose.psd/irasterimagepixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageRawDataLoader](../../com.aspose.psd/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

래스터 이미지 픽셀 로더.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | 픽셀을 부분적으로 로드합니다 (블록 단위). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


픽셀을 부분적으로 로드합니다 (블록 단위).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀을 로드할 사각형. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | 부분 로더입니다. |

