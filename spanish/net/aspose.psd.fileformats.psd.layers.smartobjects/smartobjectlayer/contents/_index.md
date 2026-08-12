---
title: "SmartObjectLayer.Contents"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad SmartObjectLayer. Obtiene o establece el contenido de la capa de objeto inteligente. El contenido del objeto inteligente incrustado es el archivo de imagen sin procesar incrustado Data y sus propiedades. El contenido del objeto inteligente vinculado es el contenido sin procesar del archivo de imagen vinculado si está disponible y sus propiedades LiFeDataSource. No admitimos la carga desde la Adobe Photoshop Graphics Library cuando IsLibraryLink es verdadero. Para archivos vinculados normales, primero usamos RelativePath para buscar el archivo de forma relativa a la ruta de la imagen fuente SourceImagePath; si no está disponible, buscamos en FullPath; si tampoco, buscamos el archivo vinculado en el mismo directorio donde está nuestra imagen SourceImagePath"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
{{< psd/tize >}}
## SmartObjectLayer.Contents property

Obtiene o establece el contenido de la capa de objeto inteligente. El contenido del objeto inteligente incrustado es el archivo de imagen sin procesar incrustado: [`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) y sus propiedades. El contenido del objeto inteligente vinculado es el contenido sin procesar del archivo de imagen vinculado si está disponible y sus propiedades: [`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). No admitimos la carga desde la Adobe� Photoshop� �� Graphics Library cuando [`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) es verdadero. Para archivos vinculados normales, primero usamos [`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) para buscar el archivo de forma relativa a la ruta de la imagen fuente SourceImagePath, si no está disponible buscamos en [`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), si tampoco entonces buscamos el archivo vinculado en el mismo directorio donde está nuestra imagen: SourceImagePath.

```csharp
public byte[] Contents { get; set; }
```

### Property Value

El contenido de la capa de objeto inteligente como byte[].

### Excepciones

| excepción | condición |
| --- | --- |
| NotSupportedException | No se pueden obtener los contenidos de la biblioteca Adobe� Photoshop� ��. |

## Ejemplos

El siguiente código demuestra el soporte de objetos inteligentes incrustados.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Este ejemplo demuestra cómo cambiar la capa de objeto inteligente en el archivo PSD y exportar/actualizar el contenido original incrustado del objeto inteligente.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Exportemos la imagen del objeto inteligente incrustado de la capa de objeto inteligente del PSD
        smartObjectLayer.ExportContents(exportPath);

        // Verifiquemos si la imagen original se guarda correctamente
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Invertamos la imagen original del objeto inteligente
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Reemplacemos la imagen del objeto inteligente incrustada en la capa del PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Verifiquemos si la imagen actualizada se guarda correctamente
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ver también

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


