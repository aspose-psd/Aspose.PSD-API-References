---
title: MaskRectangle
second_title: Referencia de API de Aspose.PSD para .NET
description: Obtiene o establece la máscaraRectangleaspose.psd/rectanglede la máscara de capa en el archivo PSD. Toma las propiedades izquierda derecha superior e inferior y creaRectangleaspose.psd/rectangle
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Obtiene o establece la máscara[`Rectangle`](../../../aspose.psd/rectangle)de la máscara de capa en el archivo PSD. Toma las propiedades izquierda, derecha, superior e inferior y crea[`Rectangle`](../../../aspose.psd/rectangle)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### El valor de la propiedad

El rectángulo de la máscara.

### Ejemplos

Este ejemplo muestra cómo obtener, actualizar, eliminar y agregar máscaras de capa ráster en el archivo de Adobe® Photoshop® mediante programación.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

string dataDir = "PSDNET640_1" + Path.DirectorySeparatorChar;

// Obtiene el valor int convertido al orden de bytes big-endian.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Obtiene el valor convertido de big endian a Int32.
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// Obtiene una máscara de trama de la capa de una imagen PSD y la guarda en un archivo
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// Agrega una máscara de trama del archivo a la capa y la guarda en la imagen en formato PSD
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // Solo agregar LayerMaskData no es suficiente para guardar correctamente porque los canales no se actualizan;
    // capa.LayerMaskData = máscara; // Esto no agrega el canal de máscara

    // Añadir (o actualizar) la máscara
    layer.AddLayerMask(maskData); // ¡Pero esto agrega/actualiza tanto la máscara como los canales!
}

// Este ejemplo muestra cómo obtener, actualizar, eliminar y agregar máscaras de capa ráster en el archivo de Adobe® Photoshop® mediante programación.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
Directory.CreateDirectory(dataDir);
var sourceFilePath = dataDir + "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Obtenga una máscara rasterizada de la capa y guárdela en un archivo
    SaveRasterMask(dataDir + "FourWithMasks2.msk", layer);

    // Cambiar la máscara de capa (invertir) y guardar la imagen
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Solo cambiar LayerMaskData es suficiente para efectuar el renderizado
    image.Save(dataDir + "FourWithMasksUpdated2.png", pngOptions);

    // Pero solo cambiar LayerMaskData no es suficiente para guardar correctamente porque los canales no se actualizan;
    layer.LayerMaskData = mask; // Esto tampoco funciona
    layer.AddLayerMask(mask); // ¡Pero esto actualiza tanto la máscara como los canales!
    image.Save(dataDir + "FourWithMasksUpdated2.psd");

    // Elimina una máscara rasterizada de la capa y guarda la imagen
    layer.LayerMaskData = null; // Solo eliminar LayerMaskData es suficiente para efectuar el renderizado pero no para guardar en formato PSD
    image.Save(dataDir + "FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // ¡Pero esto elimina tanto la máscara como el canal de la máscara!
    image.Save(dataDir + "FourWithMasksRemoved2.psd");

    // Agregue una máscara de trama del archivo a la capa y guarde la imagen
    AddRasterMask(layer, dataDir + "raster.msk");
    image.Save(dataDir + "FourWithMasksAdded2.png", pngOptions);
    image.Save(dataDir + "FourWithMasksAdded2.psd");
}
```

### Ver también

* struct [Rectangle](../../../aspose.psd/rectangle)
* class [LayerMaskData](../../layermaskdata)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata)
* asamblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
