---
title: "IImageLoader"
second_title: "Java용 Aspose.PSD API 참조"
description: "이미지 로더입니다."
type: docs
weight: 123
url: /ko/java/com.aspose.psd/iimageloader/
---
```
public interface IImageLoader
```

이미지 로더입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [load(StreamContainer streamContainer, LoadOptions loadOptions)](#load-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | loadOptions와 함께 새 이미지를 엽니다. |
### load(StreamContainer streamContainer, LoadOptions loadOptions) {#load-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract Image load(StreamContainer streamContainer, LoadOptions loadOptions)
```


loadOptions와 함께 새 이미지를 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 로드 옵션. |

**Returns:**
[Image](../../com.aspose.psd/image) - A newly opened image instance.
