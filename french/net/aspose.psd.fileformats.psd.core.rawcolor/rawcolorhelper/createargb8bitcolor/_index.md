---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode RawColorHelper. Crée une couleur ARGB de 8 bits par canal"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Crée une couleur ARGB à 8 bits par canal.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| a | Octet | La valeur du composant alpha (0-255). |
| r | Octet | La valeur du composant rouge (0-255). |
| g | Octet | La valeur du composant vert (0-255). |
| b | Octet | La valeur du composant bleu (0-255). |

### Valeur de retour

Une nouvelle instance [`RawColor`](../../rawcolor/) représentant la couleur ARGB.

## Remarques

Les composants de couleur sont empaquetés dans un entier 32 bits dans l'ordre : alpha (bits 24-31), rouge (bits 16-23), vert (bits 8-15) et bleu (bits 0-7).

### Voir aussi

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Crée une couleur ARGB à 8 bits par canal à partir de Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| drawingColor | Couleur | La couleur System.Drawing |

### Valeur de retour

Une nouvelle instance [`RawColor`](../../rawcolor/) représentant la couleur ARGB.

## Remarques

Les composants de couleur sont empaquetés dans un entier 32 bits dans l'ordre : alpha (bits 24-31), rouge (bits 16-23), vert (bits 8-15) et bleu (bits 0-7).

### Voir aussi

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


