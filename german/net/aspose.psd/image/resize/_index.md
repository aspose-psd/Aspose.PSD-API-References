---
title: "Image.Resize"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Image-Methode. Ändert die Größe des Bildes."
type: docs
weight: 200
url: /de/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Ändert die Größe des Bildes.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Der Skalierungstyp. |

### Siehe auch

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Ändert die Größe des Bildes. Der Standard‑NearestNeighbourResample wird verwendet.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |

## Beispiele

Das folgende Beispiel demonstriert, wie ein PSD‑Bild skaliert wird und welches Ergebnis wir mit Aspose.PSD erhalten.

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Siehe auch

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändert die Größe des Bildes.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| Einstellungen | ImageResizeSettings | Die Skalierungseinstellungen. |

### Siehe auch

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


