---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PsdOptions. Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. Μπορεί να είναι PSD ή PSB."
type: docs
weight: 70
url: /el/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. Μπορεί να είναι PSD ή PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

Η έκδοση μορφής αρχείου.

## Παραδείγματα

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


