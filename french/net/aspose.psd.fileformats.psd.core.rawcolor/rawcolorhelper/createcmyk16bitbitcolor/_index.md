---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode RawColorHelper. Crée une couleur CMYK de 16 bits par canal."
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Crée une couleur CMJN de 16 bits par canal.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| c | UInt16 | La valeur du composant cyan (0-65535). |
| m | UInt16 | La valeur du composant magenta (0-65535). |
| y | UInt16 | La valeur du composant jaune (0-65535). |
| k | UInt16 | La valeur du composant clé (noir) (0-65535). |

### Valeur de retour

Une nouvelle instance [`RawColor`](../../rawcolor/) représentant la couleur CMYK.

## Remarques

Les composants de couleur sont empaquetés dans un entier 64 bits dans l'ordre : cyan (bits 48-63), magenta (bits 32-47), jaune (bits 16-31) et clé/noir (bits 0-15).

### Voir aussi

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


