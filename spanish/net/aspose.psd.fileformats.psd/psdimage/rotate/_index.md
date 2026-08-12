---
title: "PsdImage.Rotate"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método PsdImage. Rota la imagen alrededor del centro"
type: docs
weight: 670
url: /es/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

Rota la imagen alrededor del centro.

```csharp
public override void Rotate(float angle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | Single | Ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

## Ejemplos

El siguiente código demuestra la capacidad de rotar la imagen por un valor de ángulo específico.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotación de la imagen completa
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Rotación de capa
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Ver también

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Rota la imagen alrededor del centro.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ángulo | Single | Ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | Boolean | si se establece en `true` el tamaño de la imagen cambiará según las proyecciones del rectángulo girado (puntos de esquina); en caso contrario, las dimensiones permanecerán sin cambios y solo se rotará el contenido interno de la imagen. |
| backgroundColor | Color | Color del fondo. |

### Ver también

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


