---
title: Image.Resize
second_title: Aspose.PSD für .NET-API-Referenz
description: Image methode. Ändert die Bildgröße. Der StandardLeftTopToLeftTopwird verwendet.
type: docs
weight: 190
url: /de/net/aspose.psd/image/resize/
---
## Resize(int, int) {#resize}

Ändert die Bildgröße. Der StandardLeftTopToLeftTopwird verwendet.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |

### Beispiele

Das folgende Beispiel zeigt, wie die Größe des PSD-Bildes geändert wird, und das Ergebnis erhalten wir durch Aspose.PSD

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

### Siehe auch

* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Ändert die Bildgröße.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Der Größenänderungstyp. |

### Siehe auch

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändert die Bildgröße.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| settings | ImageResizeSettings | Die Größenänderungseinstellungen. |

### Siehe auch

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)


