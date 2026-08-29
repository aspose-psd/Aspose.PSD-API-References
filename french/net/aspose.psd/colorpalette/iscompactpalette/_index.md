---
title: "ColorPalette.IsCompactPalette"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété ColorPalette. Obtient ou définit une valeur indiquant si la palette compacte est utilisée"
type: docs
weight: 60
url: /fr/net/aspose.psd/colorpalette/iscompactpalette/
---
{{< psd/tize >}}
## ColorPalette.IsCompactPalette property

Obtient ou définit une valeur indiquant si une palette compacte est utilisée.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` si la palette compacte est utilisée ; sinon, `false`.

## Remarques

Une palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible, ou en d'autres termes, l'image sera plus compacte et occupera moins d'espace ; sinon il y aura 2^BitsPerPixel entrées et l'image réservera plus d'espace pour toutes les entrées de palette possibles. Définir cette valeur sur true et modifier les entrées de palette peut entraîner une pénalité de performance puisque des déplacements de données peuvent se produire, donc utilisez-le avec précaution.

### Voir aussi

* class [ColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


