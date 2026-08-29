---
title: "IImageCreatorDescriptor"
second_title: "Java용 Aspose.PSD API 참조"
description: "생성기 속성을 지정하는 이미지 생성기 설명자입니다."
type: docs
weight: 119
url: /ko/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

이미지 생성자 설명자는 생성자 속성을 지정합니다. 생성자 설명자는 각 이미지 생성자 인스턴스를 메모리에 보관해야 하는 필요성과 멀티스레딩 문제를 해결하기 위해 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | 이미지 생성자가 imageOptions를 사용하여 새 이미지를 만들 수 있는지 여부를 결정합니다. |
| [createInstance()](#createInstance--) | 새 생성자 인스턴스를 생성합니다. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


이미지 생성자가 imageOptions를 사용하여 새 이미지를 만들 수 있는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 이미지 옵션. |

**Returns:**
boolean - 이 설명자에 의해 생성된 이미지 생성자가 지정된 imageOptions를 사용하여 이미지 데이터를 생성할 수 있으면 true; 그렇지 않으면 false.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


새 생성자 인스턴스를 생성합니다.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
