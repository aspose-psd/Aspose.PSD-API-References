---
title: Image.Resize
second_title: Aspose.PSD per riferimento API .NET
description: Image metodo. Ridimensiona limmagine. Il predefinitoLeftTopToLeftTopviene utilizzato.
type: docs
weight: 190
url: /it/net/aspose.psd/image/resize/
---
## Resize(int, int) {#resize}

Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |

### Esempi

L'esempio seguente mostra come ridimensionare l'immagine PSD e il risultato ottenuto da Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Guarda anche

* class [Image](../)
* spazio dei nomi [Aspose.PSD](../../image/)
* assemblea [Aspose.PSD](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Ridimensiona l'immagine.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| resizeType | ResizeType | Il tipo di ridimensionamento. |

### Guarda anche

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* spazio dei nomi [Aspose.PSD](../../image/)
* assemblea [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ridimensiona l'immagine.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| settings | ImageResizeSettings | Le impostazioni di ridimensionamento. |

### Guarda anche

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* spazio dei nomi [Aspose.PSD](../../image/)
* assemblea [Aspose.PSD](../../../)


