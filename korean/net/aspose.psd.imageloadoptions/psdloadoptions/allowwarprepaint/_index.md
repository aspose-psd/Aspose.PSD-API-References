---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdLoadOptions 속성. 왜곡 변환을 적용하거나 적용하지 않은 렌더링 이미지로 저장할지 여부를 가져오거나 설정합니다."
type: docs
weight: 30
url: /ko/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

왜곡 변환 여부에 관계없이 렌더링된 이미지와 함께 저장할지 여부를 가져오거나 설정합니다.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true`이면 왜곡 변환으로 이미지를 렌더링하고, `false`이면 그렇지 않습니다.

## 예제

다음 코드는 왜곡 효과 렌더링을 보여줍니다.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### 또 보기

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


