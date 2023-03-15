---
title: Image.Resize
second_title: Aspose.PSD för .NET API-referens
description: Image metod. Ändrar storlek på bilden.
type: docs
weight: 190
url: /sv/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Ändrar storlek på bilden.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| resizeType | ResizeType | Storleksändringstypen. |

### Se även

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Ändrar storleken på bilden. StandardenLeftTopToLeftTopanvänds.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |

### Exempel

Följande exempel visar hur man ändrar storlek på PSD-bild och resultat som vi får av Aspose.PSD

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

### Se även

* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändrar storlek på bilden.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| settings | ImageResizeSettings | Ändra storleksinställningar. |

### Se även

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)


