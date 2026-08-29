---
title: "Txt2Resource.AddTextRecord"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Txt2Resource 메서드. 텍스트 레코드를 Resource에 추가하고 텍스트 레코드의 ID를 반환합니다."
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
{{< psd/tize >}}
## Txt2Resource.AddTextRecord method

텍스트 레코드를 Resource에 추가하고 텍스트 레코드의 ID를 반환합니다.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 텍스트 | String | 레코드 텍스트. |
| bounds | RectangleF | 경계. |

### 반환 값

리소스에 대한 텍스트 레코드의 Id를 반환합니다

### 예외

| 예외 | 조건 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 알 수 없는 Txt2 리소스 버전입니다. |

## 예제

다음 코드는 새로운 ITextStyle 속성 지원을 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

string srcFile = "A.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    var textLayer = (TextLayer)psdImage.Layers[1];
    textLayer.UpdateText("abc");

    psdImage.Save(outputFile);
}

// 값 확인
using (var srcImage = (PsdImage)Image.Load(srcFile))
{
    var srcTextLayer = (TextLayer)srcImage.Layers[1];
    var etalonStyle = srcTextLayer.TextData.Items[0].Style;

    using (var outImage = (PsdImage)Image.Load(outputFile))
    {
        var outTextLayer = (TextLayer)outImage.Layers[1];
        var resultStyle = outTextLayer.TextData.Items[0].Style;

        AssertAreEqual(etalonStyle.AutoLeading, resultStyle.AutoLeading);
        AssertAreEqual(etalonStyle.FontIndex, resultStyle.FontIndex);
        AssertAreEqual(etalonStyle.Underline, resultStyle.Underline);
        AssertAreEqual(etalonStyle.Strikethrough, resultStyle.Strikethrough);
        AssertAreEqual(etalonStyle.AutoKerning, resultStyle.AutoKerning);
        AssertAreEqual(etalonStyle.StandardLigatures, resultStyle.StandardLigatures);
        AssertAreEqual(etalonStyle.DiscretionaryLigatures, resultStyle.DiscretionaryLigatures);
        AssertAreEqual(etalonStyle.ContextualAlternates, resultStyle.ContextualAlternates);
        AssertAreEqual(etalonStyle.LanguageIndex, resultStyle.LanguageIndex);
        AssertAreEqual(etalonStyle.VerticalScale, resultStyle.VerticalScale);
        AssertAreEqual(etalonStyle.HorizontalScale, resultStyle.HorizontalScale);
        AssertAreEqual(etalonStyle.Fractions, resultStyle.Fractions);
    }
}
```

### 또 보기

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


