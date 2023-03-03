---
title: RasterImage.Crop
second_title: Aspose.PSD per riferimento API .NET
description: RasterImage metodo. Ritaglia il rettangolo specificato.
type: docs
weight: 240
url: /it/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Ritaglia il rettangolo specificato.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | Rectangle | Il rettangolo. |

### Esempi

L'esempio di codice seguente mostra come ritagliare un'immagine e salvarla.

```csharp
[C#]

// Implementa il metodo Crop corretto per i file PSD.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Guarda anche

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* spazio dei nomi [Aspose.PSD](../../rasterimage/)
* assemblea [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Ritaglia l'immagine con spostamenti.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftShift | Int32 | Il turno di sinistra. |
| rightShift | Int32 | Il turno giusto. |
| topShift | Int32 | Il turno superiore. |
| bottomShift | Int32 | Lo spostamento in basso. |

### Guarda anche

* class [RasterImage](../)
* spazio dei nomi [Aspose.PSD](../../rasterimage/)
* assemblea [Aspose.PSD](../../../)


