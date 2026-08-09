---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdOptions-Eigenschaft. Gibt die Dateiformatversion zurück oder legt sie fest. Sie kann PSD oder PSB sein."
type: docs
weight: 70
url: /de/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

Liest oder setzt die Dateiformatversion. Sie kann PSD oder PSB sein.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

Die Dateiformatversion.

## Beispiele

Das folgende Beispiel zeigt die Möglichkeit, PSD-Dateien in PSB zu konvertieren und umgekehrt.

```csharp
[C#]

string sourceFilePathPsb = "2layers.psb";
string outputFilePathPsd = "ConvertFromPsb.psd";
using (Image img = Image.Load(sourceFilePathPsb))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psd };
    img.Save(outputFilePathPsd, options);
}

string sourceFilePathPsd = "2layers.psd";
string outputFilePathPsb = "ConvertFromPsd.psb";
using (Image img = Image.Load(sourceFilePathPsd))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psb };
    img.Save(outputFilePathPsb, options);
}
```

### Siehe auch

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


