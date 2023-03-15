---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD per riferimento API .NET
description: PsdOptions proprietà. Ottiene o imposta la versione del formato del file. Può essere PSD o PSB.
type: docs
weight: 60
url: /it/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

Ottiene o imposta la versione del formato del file. Può essere PSD o PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Valore della proprietà

La versione del formato del file.

### Esempi

L'esempio seguente mostra la possibilità di convertire file PSD in PSB e viceversa.

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

### Guarda anche

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* spazio dei nomi [Aspose.PSD.ImageOptions](../../psdoptions/)
* assemblea [Aspose.PSD](../../../)


