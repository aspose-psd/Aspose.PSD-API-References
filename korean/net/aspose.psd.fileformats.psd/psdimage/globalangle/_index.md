---
title: PsdImage.GlobalAngle
second_title: .NET API 참조용 Aspose.PSD
description: PsdImage 재산. 전역 각도를 가져오거나 설정합니다.
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

전역 각도를 가져오거나 설정합니다.

```csharp
public int GlobalAngle { get; set; }
```

### 예

다음 코드는 전역 각도 값을 변경하기 위한 PsdImage.GlobalAngle 속성에 대한 지원을 보여줍니다.

```csharp
[C#]

// DropShadowEffect.UseGlobalLight 속성이 'true'인 경우 DropShadowEffect 객체는 PsdImage.GlobalAngle 속성의 각도 값을 사용합니다.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### 또한보십시오

* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)


