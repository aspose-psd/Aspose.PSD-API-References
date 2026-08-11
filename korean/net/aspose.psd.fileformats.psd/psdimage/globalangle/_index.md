---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 속성. 전역 각도를 가져오거나 설정합니다"
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

전역 각도를 가져오거나 설정합니다.

```csharp
public int GlobalAngle { get; set; }
```

## 예제

다음 코드는 전역 각도 값을 변경하기 위한 PsdImage.GlobalAngle 속성 지원을 보여줍니다.

```csharp
[C#]

// DropShadowEffect.UseGlobalLight 속성이 'true'이면, DropShadowEffect 객체는 PsdImage.GlobalAngle 속성의 각도 값을 사용합니다.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### 또 보기

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


