---
title: "SolidGradient.RemoveColorPoint"
second_title: "Aspose.PSD for .NET API Referansı"
description: "SolidGradient yöntemi. Renk noktasını kaldırır"
type: docs
weight: 80
url: /tr/net/aspose.psd.fileformats.psd.layers.gradient/solidgradient/removecolorpoint/
---
{{< psd/tize >}}
## SolidGradient.RemoveColorPoint method

Renk noktasını kaldırır.

```csharp
public void RemoveColorPoint(IGradientColorPoint point)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nokta | IGradientColorPoint | Nokta. |

## Örnekler

Aşağıdaki kod, RawColor oluşturmak için RawColorHelper sınıfının kullanımını gösterir.

```csharp
[C#]

Argb8BitColor();
Argb8BitColorSimple();
Argb16BitColor();
Cmyk8BitColor();
Cmyk16Bit();

// RawColorHelper.CreateArgb8BitColor metodunu parametresiz ve bileşen adları olmadan test eder
void Argb8BitColor()
{
    var color = RawColorHelper.CreateArgb8BitColor(0, 0, 0, 0);

    if (color.GetBitDepth() != 32)
        throw new Exception($"BitDepth mismatch. Expected: 32, Actual: {color.GetBitDepth()}");

    if (color.GetColorModeName() != "ARGB")
        throw new Exception($"ColorModeName mismatch. Expected: ARGB, Actual: {color.GetColorModeName()}");

    if (color.Components.Length != 4)
        throw new Exception($"Components length mismatch. Expected: 4, Actual: {color.Components.Length}");

    string[] expectedNames = { "A Alpha", "R Red", "G Green", "B Blue" };
    for (int i = 0; i < 4; i++)
    {
        if (color.Components[i].FullName != expectedNames[i])
            throw new Exception($"Component[{i}] FullName mismatch. Expected: {expectedNames[i]}, Actual: {color.Components[i].FullName}");

        if ((int)color.Components[i].Value != 0)
            throw new Exception($"Component[{i}] Value mismatch. Expected: 0, Actual: {(int)color.Components[i].Value}");
    }
}

// RawColorHelper.CreateArgb8BitColor metodunu System.Drawing.Color parametresiyle test eder
void Argb8BitColorSimple()
{
    var sysColor = Color.FromArgb(15, 25, 35, 45);
    var color = RawColorHelper.CreateArgb8BitColor(sysColor);

    if (color.GetBitDepth() != 32)
        throw new Exception($"BitDepth mismatch. Expected: 32, Actual: {color.GetBitDepth()}");

    if (color.GetColorModeName() != "ARGB")
        throw new Exception($"ColorModeName mismatch. Expected: ARGB, Actual: {color.GetColorModeName()}");

    if (color.GetAsInt() != sysColor.ToArgb())
        throw new Exception($"GetAsInt mismatch. Expected: {sysColor.ToArgb()}, Actual: {color.GetAsInt()}");
}

// RawColorHelper.CreateArgb16BitColor metodunu test eder
void Argb16BitColor()
{
    var color = RawColorHelper.CreateArgb16BitColor(1000, 2000, 3000, 4000);

    if (color.GetBitDepth() != 64)
        throw new Exception($"BitDepth mismatch. Expected: 64, Actual: {color.GetBitDepth()}");

    if (color.GetColorModeName() != "ARGB")
        throw new Exception($"ColorModeName mismatch. Expected: ARGB, Actual: {color.GetColorModeName()}");

    if (color.Components.Length != 4)
        throw new Exception($"Components length mismatch. Expected: 4, Actual: {color.Components.Length}");

    if (color.Components[0].FullName != "A Alpha")
        throw new Exception($"Component[0] FullName mismatch. Expected: A Alpha, Actual: {color.Components[0].FullName}");

    if ((int)color.Components[0].Value != 1000)
        throw new Exception($"Component[0] Value mismatch. Expected: 1000, Actual: {(int)color.Components[0].Value}");

    if (color.Components[1].FullName != "R Red")
        throw new Exception($"Component[1] FullName mismatch. Expected: R Red, Actual: {color.Components[1].FullName}");

    if ((int)color.Components[1].Value != 2000)
        throw new Exception($"Component[1] Value mismatch. Expected: 2000, Actual: {(int)color.Components[1].Value}");

    if (color.Components[2].FullName != "G Green")
        throw new Exception($"Component[2] FullName mismatch. Expected: G Green, Actual: {color.Components[2].FullName}");

    if ((int)color.Components[2].Value != 3000)
        throw new Exception($"Component[2] Value mismatch. Expected: 3000, Actual: {(int)color.Components[2].Value}");

    if (color.Components[3].FullName != "B Blue")
        throw new Exception($"Component[3] FullName mismatch. Expected: B Blue, Actual: {color.Components[3].FullName}");

    if ((int)color.Components[3].Value != 4000)
        throw new Exception($"Component[3] Value mismatch. Expected: 4000, Actual: {(int)color.Components[3].Value}");
}

// RawColorHelper.CreateCmyk8BitColor metodunu test eder
void Cmyk8BitColor()
{
    var color = RawColorHelper.CreateCmyk8BitColor(10, 20, 30, 40);

    if (color.GetBitDepth() != 32)
        throw new Exception($"BitDepth mismatch. Expected: 32, Actual: {color.GetBitDepth()}");

    if (color.GetColorModeName() != "CMYK")
        throw new Exception($"ColorModeName mismatch. Expected: CMYK, Actual: {color.GetColorModeName()}");

    if (color.Components.Length != 4)
        throw new Exception($"Components length mismatch. Expected: 4, Actual: {color.Components.Length}");

    if ((int)color.Components[0].Value != 10)
        throw new Exception($"Component[0] Value mismatch. Expected: 10, Actual: {(int)color.Components[0].Value}");

    if ((int)color.Components[1].Value != 20)
        throw new Exception($"Component[1] Value mismatch. Expected: 20, Actual: {(int)color.Components[1].Value}");

    if ((int)color.Components[2].Value != 30)
        throw new Exception($"Component[2] Value mismatch. Expected: 30, Actual: {(int)color.Components[2].Value}");

    if ((int)color.Components[3].Value != 40)
        throw new Exception($"Component[3] Value mismatch. Expected: 40, Actual: {(int)color.Components[3].Value}");
}

// RawColorHelper.CreateCmyk16BitBitColor metodunu test eder
void Cmyk16Bit()
{
    var color = RawColorHelper.CreateCmyk16BitBitColor(1000, 2000, 3000, 4000);

    if (color.GetBitDepth() != 64)
        throw new Exception($"BitDepth mismatch. Expected: 64, Actual: {color.GetBitDepth()}");

    if (color.GetColorModeName() != "CMYK")
        throw new Exception($"ColorModeName mismatch. Expected: CMYK, Actual: {color.GetColorModeName()}");

    if (color.Components.Length != 4)
        throw new Exception($"Components length mismatch. Expected: 4, Actual: {color.Components.Length}");

    if ((int)color.Components[0].Value != 1000)
        throw new Exception($"Component[0] Value mismatch. Expected: 1000, Actual: {(int)color.Components[0].Value}");

    if ((int)color.Components[1].Value != 2000)
        throw new Exception($"Component[1] Value mismatch. Expected: 2000, Actual: {(int)color.Components[1].Value}");

    if ((int)color.Components[2].Value != 3000)
        throw new Exception($"Component[2] Value mismatch. Expected: 3000, Actual: {(int)color.Components[2].Value}");

    if ((int)color.Components[3].Value != 4000)
        throw new Exception($"Component[3] Value mismatch. Expected: 4000, Actual: {(int)color.Components[3].Value}");
}
```

### Ayrıca Bakınız

* interface [IGradientColorPoint](../../../aspose.psd.fileformats.psd.layers/igradientcolorpoint/)
* class [SolidGradient](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../../)


