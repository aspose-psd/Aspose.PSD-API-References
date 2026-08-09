---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode RawColorHelper. Crée une couleur CMYK de 8 bits par canal"
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Crée une couleur CMJN de 8 bits par canal.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| c | Octet | La valeur du composant cyan (0-255). |
| m | Octet | La valeur du composant magenta (0-255). |
| y | Octet | La valeur du composant jaune (0-255). |
| k | Octet | La valeur du composant clé (noir) (0-255). |

### Valeur de retour

Une nouvelle instance [`RawColor`](../../rawcolor/) représentant la couleur CMYK.

## Remarques

Les composants de couleur sont empaquetés dans un entier de 32 bits dans l'ordre : cyan (bits 24-31), magenta (bits 16-23), jaune (bits 8-15) et clé/noir (bits 0-7).

### Voir aussi

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


