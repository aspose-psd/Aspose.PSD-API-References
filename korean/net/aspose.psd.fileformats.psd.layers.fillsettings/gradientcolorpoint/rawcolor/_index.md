---
title: "GradientColorPoint.RawColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "GradientColorPoint 속성. 원시 색상을 가져오거나 설정합니다"
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/rawcolor/
---
{{< psd/tize >}}
## GradientColorPoint.RawColor property

원시 색상을 가져오거나 설정합니다.

```csharp
public RawColor RawColor { get; set; }
```

### Property Value

원시 색상입니다.

## 예제

다음 코드는 구식 Color 구조체 대신 RawColor 클래스를 지원하는 예시를 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### 또 보기

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


