---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageAttributes-metoden. Ställer in wrap mode som används för att bestämma hur en textur ska tileas över en form eller vid formgränser. En textur tileas över en form för att fylla den när texturen är mindre än den form den fyller."
type: docs
weight: 210
url: /sv/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

Ställer in wrap-läget som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | WrapMode | An element of [`WrapMode`](../../wrapmode/) som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |

### Se även

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Ställer in wrap-läget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | WrapMode | An element of [`WrapMode`](../../wrapmode/) som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |
| color | Color | Ett [`ImageAttributes`](../)-objekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är satt till Clamp och källrektangeln som skickas till DrawImage är större än själva bilden. |

### Se även

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Ställer in wrap-läget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | WrapMode | An element of [`WrapMode`](../../wrapmode/) som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |
| färg | Färg | Ett färgobjekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är satt till Clamp och källrektangeln som skickas till DrawImage är större än själva bilden. |
| Clamp | Boolean | Denna parameter har ingen effekt. Sätt den till false. |

### Se även

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


