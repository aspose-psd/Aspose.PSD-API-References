---
title: Enum AutoKerning
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.AutoKerning 열거형. Photoshop 자동 커닝 모드기호 간 거리.
type: docs
weight: 1600
url: /ko/net/aspose.psd.fileformats.psd/autokerning/
---
## AutoKerning enumeration

Photoshop 자동 커닝 모드(기호 간 거리).

```csharp
public enum AutoKerning
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Manual | `0` | 수동 커닝 값. |
| Metric | `1` | 메트릭 커닝은 디자이너가 제공하는 대부분의 글꼴에 포함된 커닝 쌍을 사용합니다. |
| Optical | `2` | 시각적 커닝은 모양에 따라 인접한 문자 사이의 간격을 조정합니다. |

### 예

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

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 집회 [Aspose.PSD](../../)


