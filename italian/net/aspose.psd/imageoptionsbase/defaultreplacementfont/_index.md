---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD per riferimento API .NET
description: ImageOptionsBase proprietà. Ottiene o imposta il carattere sostitutivo predefinito carattere che verrà utilizzato per disegnare il testo durante lesportazione in raster se il carattere del livello esistente nel file PSD non è presentato nel sistema. Per prendere il nome corretto del carattere predefinito può essere utilizzato il prossimo frammento di codice  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily famiglie  col.Families string defaultFontName  famiglie0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /it/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

Ottiene o imposta il carattere sostitutivo predefinito (carattere che verrà utilizzato per disegnare il testo durante l'esportazione in raster, se il carattere del livello esistente nel file PSD non è presentato nel sistema). Per prendere il nome corretto del carattere predefinito può essere utilizzato il prossimo frammento di codice : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] famiglie = col.Families; string defaultFontName = famiglie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Valore della proprietà

Il font sostitutivo predefinito.

### Esempi

L'esempio seguente mostra come utilizzare la proprietà DefaultReplacementFont per modificare il carattere sostitutivo predefinito.

```csharp
[C#]

// Per favore, non installare Konstanting Font, perché questo test dovrebbe sostituire il font che non è installato
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // In questo modo puoi utilizzare caratteri diversi per output diversi 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Guarda anche

* class [ImageOptionsBase](../)
* spazio dei nomi [Aspose.PSD](../../imageoptionsbase/)
* assemblea [Aspose.PSD](../../../)


