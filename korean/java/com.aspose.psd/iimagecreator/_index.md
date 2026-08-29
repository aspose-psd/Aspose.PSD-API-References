---
title: "IImageCreator"
second_title: "Java용 Aspose.PSD API 참조"
description: "이미지 생성기입니다."
type: docs
weight: 118
url: /ko/java/com.aspose.psd/iimagecreator/
---
```
public interface IImageCreator
```

이미지 생성기입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-) | imageOptions를 사용하여 새 이미지 인스턴스를 생성합니다. |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


imageOptions를 사용하여 새 이미지 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 이미지 데이터를 생성할 스트림 컨테이너입니다. |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 이미지 옵션. |
| 너비 | int | 새 이미지의 너비 |
| 높이 | int | 새 이미지의 높이 |

**Returns:**
[Image](../../com.aspose.psd/image) - A new image instance.
