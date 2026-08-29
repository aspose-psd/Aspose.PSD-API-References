---
title: "IPartialPixelLoader"
second_title: "Java용 Aspose.PSD API 참조"
description: "픽셀이 부분적으로 로드되는 것을 준수합니다."
type: docs
weight: 132
url: /ko/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

픽셀이 부분적으로 로드되는 것을 준수합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | 로드된 픽셀을 처리합니다. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


로드된 픽셀을 처리합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 픽셀 사각형. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | 픽셀. |
| start | [Point](../../com.aspose.psd/point) | 시작 픽셀 지점. (left,top)과 같지 않으면 전체 사각형이 아니라는 의미입니다. |
| end | [Point](../../com.aspose.psd/point) | 끝 픽셀 지점. (right,bottom)과 같지 않으면 전체 사각형이 아니라는 의미입니다. |

