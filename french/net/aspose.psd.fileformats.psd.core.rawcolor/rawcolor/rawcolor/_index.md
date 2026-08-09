---
title: "RawColor.RawColor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur RawColor. Initialise une nouvelle instance de la classe RawColor"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

Initialise une nouvelle instance de la classe [`RawColor`](../).

```csharp
public RawColor(ColorComponent[] components)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| composants | ColorComponent[] | Les composants de couleur personnalisés. |

### Voir aussi

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

Initialise une nouvelle instance de la classe [`RawColor`](../) à partir du format de données de pixel en utilisant des modes de couleur prédéfinis.

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | Le format de données de pixel. |
| colorMode | Int16 | Mode pour la couleur à suivre. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Le nombre de canaux diffère du PixelFormat, l'index des canaux ne peut pas être obtenu. Veuillez créer RawColor avec l'argument Components' Array. |

### Voir aussi

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


