---
title: "IImageLoaderDescriptor"
second_title: "Java용 Aspose.PSD API 참조"
description: "로더 속성을 지정하는 이미지 로더 설명자입니다."
type: docs
weight: 124
url: /ko/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

로드 속성을 지정하는 이미지 로더 디스크립터입니다. 로더 디스크립터는 각 이미지 로더 인스턴스를 메모리에 보관해야 하는 필요성과 멀티스레딩 문제를 해결하기 위해 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | 이미지 로더가 지정된 스트림에서 새 이미지를 읽을 수 있는지, 그리고 선택적으로  loadOptions  를 사용할 수 있는지를 결정합니다. |
| [createInstance()](#createInstance--) | 새 로더 인스턴스를 생성합니다. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


이미지 로더가 지정된 스트림에서 새 이미지를 읽을 수 있는지, 그리고 선택적으로  loadOptions  를 사용할 수 있는지를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |   loadOptions  로 지정된 파일 형식 세부 정보입니다.  loadOptions  는 null 일 수 있습니다. |

**Returns:**
boolean - 이 디스크립터에 의해 생성된 이미지 로더가 스트림에서 이미지를 읽을 수 있으면  true  , 그렇지 않으면  false  .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


새 로더 인스턴스를 생성합니다.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
