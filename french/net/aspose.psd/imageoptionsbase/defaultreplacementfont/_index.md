---
title: "ImageOptionsBase.DefaultReplacementFont"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété ImageOptionsBase. Obtient ou définit la police de remplacement par défaut qui sera utilisée pour dessiner le texte lors de l'exportation en raster si la police de calque existante dans le fichier PSD n'est pas présente dans le système. Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé : System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName"
type: docs
weight: 20
url: /fr/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
{{< psd/tize >}}
## ImageOptionsBase.DefaultReplacementFont property

Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Property Value

La police de remplacement par défaut.

## Exemples

L'exemple suivant montre comment utiliser la propriété DefaultReplacementFont pour modifier la police de remplacement par défaut.

```csharp
[C#]

// Veuillez ne pas installer la police Konstanting, car ce test doit remplacer une police qui n'est pas installée.
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
{
    // De cette façon, vous pouvez utiliser différentes polices pour différentes sorties.
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Voir aussi

* class [ImageOptionsBase](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


