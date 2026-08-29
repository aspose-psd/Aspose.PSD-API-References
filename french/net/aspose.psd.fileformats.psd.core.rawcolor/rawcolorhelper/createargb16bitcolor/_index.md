---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode RawColorHelper. Crée une couleur ARGB de 16 bits par canal"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Crée une couleur ARGB à 16 bits par canal.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| a | UInt16 | La valeur du composant alpha (0-65535). |
| r | UInt16 | La valeur du composant rouge (0-65535). |
| g | UInt16 | La valeur du composant vert (0-65535). |
| b | UInt16 | La valeur du composant bleu (0-65535). |

### Valeur de retour

Une nouvelle instance [`RawColor`](../../rawcolor/) représentant la couleur ARGB.

## Remarques

Les composants de couleur sont empaquetés dans un entier de 64 bits dans l'ordre : alpha (bits 48-63), rouge (bits 32-47), vert (bits 16-31) et bleu (bits 0-15).

### Voir aussi

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


