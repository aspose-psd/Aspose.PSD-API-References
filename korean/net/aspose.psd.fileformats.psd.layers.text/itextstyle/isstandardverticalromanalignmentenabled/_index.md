---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ITextStyle 속성. 표준 수직 로마 정렬을 가져오거나 설정합니다. 이는 BaselineDirection 리소스 값을 기반으로 하며 텍스트 방향이 수직일 때만 적용됩니다"
type: docs
weight: 170
url: /ko/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

표준 수직 로마 정렬을 가져오거나 설정합니다. 이는 BaselineDirection 리소스 값을 기반으로 하며 텍스트 방향이 수직일 때만 적용됩니다.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## 예제

다음 코드는 새로운 IsStandardVerticalRomanAlignmentEnabled 속성의 지원을 보여줍니다.

```csharp
[C#]

// 다음 코드는 새로운 IsStandardVerticalRomanAlignmentEnabled 속성을 편집할 수 있는 기능을 보여줍니다.
// 이는 현재 렌더링에 영향을 주지 않으며, 속성 값을 편집할 수 있게 할 뿐입니다.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // 올바른 읽기
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // 올바른 읽기
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### 또 보기

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


