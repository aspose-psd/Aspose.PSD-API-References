---
title: RasterCachedImage.Resize
second_title: Aspose.PSD per riferimento API .NET
description: RasterCachedImage metodo. Ridimensiona limmagine.
type: docs
weight: 120
url: /it/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Ridimensiona l'immagine.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| resizeType | ResizeType | Il tipo di ridimensionamento. |

### Esempi

Il codice seguente mostra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente mostra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente illustra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente mostra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente mostra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente illustra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Guarda anche

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* spazio dei nomi [Aspose.PSD](../../rastercachedimage/)
* assemblea [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ridimensiona l'immagine.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| settings | ImageResizeSettings | Le impostazioni di ridimensionamento. |

### Guarda anche

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* spazio dei nomi [Aspose.PSD](../../rastercachedimage/)
* assemblea [Aspose.PSD](../../../)


