---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdLoadOptions 속성. 레이어가 수정되지 않은 경우 렌더링 중 원본 레이어 픽셀을 보존할지 여부를 가져오거나 설정합니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

레이어가 수정되지 않은 경우 렌더링 중 원본 레이어 픽셀을 보존할지 여부를 가져오거나 설정합니다.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true`이면 변경되지 않은 레이어의 원본 픽셀을 유지하고, 그렇지 않으면 `false`.

## 예제

다음 코드는 변경 전에 레이어의 자동 재페인팅을 방지하는 새로운 동작을 보여줍니다.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### 또 보기

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


