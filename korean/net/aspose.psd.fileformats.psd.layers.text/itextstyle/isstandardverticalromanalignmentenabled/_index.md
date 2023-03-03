---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: .NET API 참조용 Aspose.PSD
description: ITextStyle 재산. 표준 세로 로마자 정렬을 가져오거나 설정합니다. 이것은 BaselineDirection 리소스 값을 기반으로 하며 텍스트 방향이 다음과 같은 경우에만 적용됩니다.Vertical .
type: docs
weight: 170
url: /ko/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

표준 세로 로마자 정렬을 가져오거나 설정합니다. 이것은 BaselineDirection 리소스 값을 기반으로 하며 텍스트 방향이 다음과 같은 경우에만 적용됩니다.Vertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### 예

다음 코드는 새로운 IsStandardVerticalRomanAlignmentEnabled 속성의 지원을 보여줍니다.

```csharp
[C#]

// 다음 코드는 새 IsStandardVerticalRomanAlignmentEnabled 속성을 편집하는 기능을 보여줍니다.
// 현재 렌더링에는 영향을 미치지 않으며 속성 값을 편집할 수만 있습니다.

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

### 또한보십시오

* interface [ITextStyle](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* 집회 [Aspose.PSD](../../../)


