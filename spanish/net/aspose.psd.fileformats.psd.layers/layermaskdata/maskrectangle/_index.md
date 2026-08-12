---
title: "LayerMaskData.MaskRectangle"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "LayerMaskData propiedad. Obtiene o establece el rectángulo de máscara de la máscara de capa en el archivo PSD. Toma las propiedades left, right, top y bottom y crea Rectangle"
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

Obtiene o establece la máscara [`Rectangle`](../../../aspose.psd/rectangle/) de la máscara de capa en el archivo PSD. Toma las propiedades left, right, top y bottom y crea [`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

El rectángulo de la máscara.

## Ejemplos

Este ejemplo muestra cómo obtener, actualizar, eliminar y agregar máscaras de capa raster en el archivo Adobe® Photoshop® de forma programática.

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

// Obtiene una máscara raster de la capa de una imagen PSD y la guarda en un archivo
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

// Agrega una máscara raster del archivo a la capa y la guarda en la imagen en formato PSD
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

    // Simplemente agregar LayerMaskData no es suficiente para guardar correctamente porque los canales no se actualizan;
    // layer.LayerMaskData = mask; // Esto no agrega el canal de máscara

    // Agregar (o actualizar) la máscara
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// Este ejemplo muestra cómo obtener, actualizar, eliminar y agregar máscaras de capa raster en el archivo Adobe® Photoshop® de forma programática.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Obtener una máscara raster de la capa y guardarla en un archivo
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Cambiar la máscara de capa (invertir) y guardar la imagen
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Simplemente cambiar LayerMaskData es suficiente para afectar la renderización
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Pero simplemente cambiar LayerMaskData no es suficiente para guardar correctamente porque los canales no se actualizan;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // Eliminar una máscara raster de la capa y guardar la imagen
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // Agregar una máscara raster del archivo a la capa y guardar la imagen
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Ver también

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


