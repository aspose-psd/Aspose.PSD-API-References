---
title: Enum PsdVersion
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.PsdVersion opsomming. Dateiformatversion
type: docs
weight: 3600
url: /de/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

Dateiformatversion

```csharp
public enum PsdVersion : byte
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Psd | `1` | Die Standard-PSD-Version. |
| Psb | `2` | Die PSB-Version. |

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

* namensraum [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Montage [Aspose.PSD](../../)


