---
title: "RasterCachedImage.Resize"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "RasterCachedImage-Methode. Ändert die Größe des Bildes"
type: docs
weight: 120
url: /de/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Ändert die Größe des Bildes.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Der Skalierungstyp. |

## Beispiele

Der folgende Code demonstriert, wie man ein Bild mit einem neuen SinC‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen Bell‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen Mitchell‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen CatmullRom‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen CubicBSpline‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen CubicConvolution‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Siehe auch

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändert die Größe des Bildes.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| Einstellungen | ImageResizeSettings | Die Skalierungseinstellungen. |

### Siehe auch

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


