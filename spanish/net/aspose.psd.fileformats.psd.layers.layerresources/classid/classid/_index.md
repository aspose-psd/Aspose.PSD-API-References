---
title: "ClassID.ClassID"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor ClassID. Inicializa una nueva instancia de la clase ClassID"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

Inicializa una nueva instancia de la clase [`ClassID`](../).

```csharp
public ClassID(byte[] classID)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classID | Byte[] | El ID de clase como una serie de bytes. |

### Ver también

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Inicializa una nueva instancia de la clase [`ClassID`](../).

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classID | Byte[] | El ID de clase como una serie de bytes. |
| isZeroLength | Boolean | si se establece en `true` [es longitud cero]. La longitud de cadena registrada es cero pero la real es cuatro. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | classID es nulo. |

### Ver también

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Inicializa una nueva instancia de la clase [`ClassID`](../).

```csharp
public ClassID(int classID)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classID | Int32 | El ID de la clase. |

### Ver también

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Inicializa una nueva instancia de la clase [`ClassID`](../).

```csharp
public ClassID(uint classID)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classID | UInt32 | El ID de la clase. |

### Ver también

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Inicializa una nueva instancia de la clase [`ClassID`](../).

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classID | String | El ID de clase en codificación ASCII. |
| isZeroLength | Boolean | si se establece en `true` [es longitud cero]. |

## Ejemplos

Este ejemplo demuestra que la capa, importada de una imagen, se convierte en una capa de objeto inteligente y el archivo PSD guardado es correcto.

```csharp
[C#]

// Prueba que la capa, importada de una imagen, se convierte en una capa de objeto inteligente y el archivo PSD guardado es correcto.

string outputFilePath = outputFolder + Path.DirectorySeparatorChar + "layerTest2.psd";
string outputPngFilePath = Path.ChangeExtension(outputFilePath, ".png");
using (PsdImage image = (PsdImage)Image.Load(baseFolder + Path.DirectorySeparatorChar + "layerTest1.psd"))
{
    string layerFilePath = baseFolder + Path.DirectorySeparatorChar + "picture.jpg";
    using (var stream = new FileStream(layerFilePath, FileMode.Open))
    {
        Layer layer = null;
        try
        {
            layer = new Layer(stream);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }

        var layer2 = image.Layers[2];
        var layer3 = image.SmartObjectProvider.ConvertToSmartObject(image.Layers.Length - 1);
        var bounds = layer3.Bounds;
        layer3.Left = (image.Width - layer3.Width) / 2;
        layer3.Top = layer2.Top;
        layer3.Right = layer3.Left + bounds.Width;
        layer3.Bottom = layer3.Top + bounds.Height;

        image.Save(outputFilePath);
        image.Save(outputPngFilePath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ver también

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Inicializa una nueva instancia de la clase [`ClassID`](../).

```csharp
public ClassID(string classID)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classID | String | El ID de clase en codificación ASCII. |

### Ver también

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


