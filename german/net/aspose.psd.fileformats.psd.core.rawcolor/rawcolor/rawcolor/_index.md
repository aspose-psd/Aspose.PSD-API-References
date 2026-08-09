---
title: "RawColor.RawColor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "RawColor-Konstruktor. Initialisiert eine neue Instanz der RawColor-Klasse."
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

Initialisiert eine neue Instanz der [`RawColor`](../)-Klasse.

```csharp
public RawColor(ColorComponent[] components)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Komponenten | ColorComponent[] | Die benutzerdefinierten Farbkomponenten. |

### Siehe auch

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

Initialisiert eine neue Instanz der [`RawColor`](../)-Klasse aus dem Pixeldatenformat unter Verwendung vordefinierter Farbmodi.

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | Das Pixeldatenformat. |
| Farbmodus | Int16 | Modus für die nachfolgende Farbe. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Die Kanalanzahl weicht vom PixelFormat ab, der Index der Kanäle kann nicht ermittelt werden. Bitte erstellen Sie RawColor mit dem Components' Array-Argument. |

### Siehe auch

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


