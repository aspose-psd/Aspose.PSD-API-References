---
title: GradientFillSettings.GradientType
second_title: Referencia de API de Aspose.PSD para .NET
description: GradientFillSettings propiedad. Obtiene o establece el tipo de gradiente.
type: docs
weight: 90
url: /es/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Obtiene o establece el tipo de gradiente.

```csharp
public GradientType GradientType { get; set; }
```

### El valor de la propiedad

El tipo de degradado.

### Ejemplos

El siguiente código guarda imágenes con diferentes tipos de degradado y muestra cómo Aspose.PSD dibuja el degradado.

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ver también

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* asamblea [Aspose.PSD](../../../)


