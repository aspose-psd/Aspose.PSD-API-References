---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageAttributes-Methode. Legt den Wrap-Modus fest, der verwendet wird, um zu entscheiden, wie eine Textur über einer Form oder an Formgrenzen gekachelt wird. Eine Textur wird über einer Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form."
type: docs
weight: 210
url: /de/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

Legt den Wrap-Modus fest, der verwendet wird, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | WrapMode | Ein Element von [`WrapMode`](../../wrapmode/), das festlegt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |

### Siehe auch

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | WrapMode | Ein Element von [`WrapMode`](../../wrapmode/), das festlegt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | Color | Ein [`ImageAttributes`](../)-Objekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modus‑Parameter auf Clamp gesetzt ist und das an DrawImage übergebene Quellrechteck größer ist als das Bild selbst. |

### Siehe auch

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | WrapMode | Ein Element von [`WrapMode`](../../wrapmode/), das festlegt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| Farbe | Farbe | Ein Farbobjekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modus‑Parameter auf Clamp gesetzt ist und das an DrawImage übergebene Quellrechteck größer ist als das Bild selbst. |
| clamp | Boolean | Dieser Parameter hat keine Wirkung. Setzen Sie ihn auf false. |

### Siehe auch

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


