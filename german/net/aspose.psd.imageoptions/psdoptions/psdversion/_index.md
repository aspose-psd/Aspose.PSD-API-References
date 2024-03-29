---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD für .NET-API-Referenz
description: PsdOptions eigendom. Ruft die Version des Dateiformats ab oder legt sie fest. Es kann PSD oder PSB sein.
type: docs
weight: 60
url: /de/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

Ruft die Version des Dateiformats ab oder legt sie fest. Es kann PSD oder PSB sein.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Eigentumswert

Die Version des Dateiformats.

### Beispiele

Das folgende Beispiel zeigt die Möglichkeit, PSD-Dateien in PSB und umgekehrt zu konvertieren.

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
* namensraum [Aspose.PSD.ImageOptions](../../psdoptions/)
* Montage [Aspose.PSD](../../../)


