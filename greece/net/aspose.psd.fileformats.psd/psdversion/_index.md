---
title: Enum PsdVersion
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.PsdVersion αρίθμηση. Μορφή αρχείου Έκδοση
type: docs
weight: 3600
url: /el/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

Μορφή αρχείου Έκδοση

```csharp
public enum PsdVersion : byte
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Psd | `1` | Η προεπιλεγμένη έκδοση PSD. |
| Psb | `2` | Η έκδοση PSB. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει τη δυνατότητα μετατροπής αρχείου PSD σε PSB και αντίστροφα.

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

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* συνέλευση [Aspose.PSD](../../)


