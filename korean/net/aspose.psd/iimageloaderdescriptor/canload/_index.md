---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "IImageLoaderDescriptor 메서드. 지정된 스트림에서 새 이미지를 읽을 수 있는지, 그리고 선택적으로 loadOptions를 사용하는지를 결정합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd/iimageloaderdescriptor/canload/
---
{{< psd/tize >}}
## IImageLoaderDescriptor.CanLoad method

지정된 스트림에서 새 이미지를 읽을 수 있는지 여부를 판단하고, 선택적으로 *loadOptions*를 사용합니다.

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | StreamContainer | 스트림 컨테이너입니다. |
| loadOptions | LoadOptions | *loadOptions*에 의해 지정된 파일 형식 세부 정보입니다. *loadOptions*는 null일 수 있습니다. |

### 반환 값

이 설명자에 의해 생성된 이미지 로더가 스트림에서 이미지를 읽을 수 있으면 `true`; 그렇지 않으면 `false`.

### 또 보기

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


