---
title: Image.Resize
second_title: Aspose.PSD voor .NET API-referentie
description: Image methode. Pas de grootte van de afbeelding aan.
type: docs
weight: 190
url: /nl/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Pas de grootte van de afbeelding aan.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | Int32 | De nieuwe breedte. |
| newHeight | Int32 | De nieuwe hoogte. |
| resizeType | ResizeType | Het formaat wijzigen type. |

### Zie ook

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Wijzigt de grootte van de afbeelding. De standaardLeftTopToLeftTopwordt gebruikt.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | Int32 | De nieuwe breedte. |
| newHeight | Int32 | De nieuwe hoogte. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u de grootte van de PSD-afbeelding kunt wijzigen en het resultaat dat we krijgen van Aspose.PSD

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

### Zie ook

* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Pas de grootte van de afbeelding aan.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | Int32 | De nieuwe breedte. |
| newHeight | Int32 | De nieuwe hoogte. |
| settings | ImageResizeSettings | De instellingen voor formaat wijzigen. |

### Zie ook

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)


