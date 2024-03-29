---
title: RasterCachedImage.Resize
second_title: Aspose.PSD für .NET-API-Referenz
description: RasterCachedImage methode. Ändert die Bildgröße.
type: docs
weight: 120
url: /de/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Ändert die Bildgröße.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Der Größenänderungstyp. |

### Beispiele

Der folgende Code zeigt, wie Sie die Größe eines Bildes mit einem neuen SinC-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie Sie die Größe eines Bilds mit einem neuen Bell-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie Sie die Größe eines Bilds mit einem neuen Mitchell-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie die Größe eines Bildes mit einem neuen CatmullRom-Größenänderungstyp geändert wird.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie Sie die Größe eines Bilds mit einem neuen CubicBSpline-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie Sie die Größe eines Bilds mit einem neuen CubicConvolution-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Siehe auch

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namensraum [Aspose.PSD](../../rastercachedimage/)
* Montage [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändert die Bildgröße.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| settings | ImageResizeSettings | Die Größenänderungseinstellungen. |

### Siehe auch

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namensraum [Aspose.PSD](../../rastercachedimage/)
* Montage [Aspose.PSD](../../../)


