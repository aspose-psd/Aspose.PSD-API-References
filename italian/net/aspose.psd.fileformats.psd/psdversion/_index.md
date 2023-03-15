---
title: Enum PsdVersion
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.PsdVersion enum. Versione formato file
type: docs
weight: 3600
url: /it/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

Versione formato file

```csharp
public enum PsdVersion : byte
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Psd | `1` | La versione PSD predefinita. |
| Psb | `2` | La versione PSB. |

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

* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assemblea [Aspose.PSD](../../)


