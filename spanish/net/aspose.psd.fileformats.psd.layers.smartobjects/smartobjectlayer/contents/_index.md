---
title: Contents
second_title: Referencia de API de Aspose.PSD para .NET
description: Obtiene o establece el contenido de la capa del objeto inteligente. El contenido del objeto inteligente incrustado es el archivo de imagen sin procesar incrustadoDataaspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data y sus propiedades. El contenido del objeto inteligente vinculado es el contenido sin procesar del archivo de imagen vinculado si está disponible y sus propiedadesLiFeDataSourceaspose.psd.fileformats.psd.layers.layerresources/lifedatasource . No admitimos la carga desde Adobe Photoshop  Biblioteca de gráficos cuandoIsLibraryLinkaspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink es verdadero. Para archivos de enlace regulares al principio usamosRelativePathaspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath para buscar el archivo relativamente en la ruta de la imagen de origenSourceImagePath  si no está disponible miramosFullPathaspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath  si no es así entonces buscamos el archivo de enlace en el mismo directorio donde está nuestra imagenSourceImagePath .
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

Obtiene o establece el contenido de la capa del objeto inteligente. El contenido del objeto inteligente incrustado es el archivo de imagen sin procesar incrustado:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data) y sus propiedades. El contenido del objeto inteligente vinculado es el contenido sin procesar del archivo de imagen vinculado si está disponible y sus propiedades:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource) . No admitimos la carga desde Adobe� Photoshop� �� Biblioteca de gráficos cuando[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink) es verdadero. Para archivos de enlace regulares, al principio, usamos[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath) para buscar el archivo relativamente en la ruta de la imagen de origenSourceImagePath , si no está disponible miramos[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath) , si no es así entonces buscamos el archivo de enlace en el mismo directorio donde está nuestra imagen:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### El valor de la propiedad

Elbyte[] contenido de la capa de objeto inteligente.

### Excepciones

| excepción | condición |
| --- | --- |
| NotSupportedException | No se puede obtener contenido de la biblioteca de Adobe� Photoshop� ��. |

### Ejemplos

El código siguiente demuestra la compatibilidad con los objetos inteligentes integrados.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Este ejemplo demuestra cómo cambiar la capa del objeto inteligente en el archivo PSD y exportar/actualizar el contenido incrustado original del objeto inteligente.
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

        // Exportemos la imagen del objeto inteligente incrustado desde la capa de objetos inteligentes PSD
        smartObjectLayer.ExportContents(exportPath);

        // Verifiquemos si la imagen original se guardó correctamente
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Vamos a invertir la imagen original del objeto inteligente
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Reemplacemos la imagen del objeto inteligente incrustado en la capa PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Verifiquemos si la imagen actualizada se guardó correctamente
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ver también

* class [SmartObjectLayer](../../smartobjectlayer)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer)
* asamblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
