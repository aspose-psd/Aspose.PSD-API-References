---
title: "Classe CmykColorHelper"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.CmykColorHelper class. Méthodes d'aide pour travailler avec la couleur CMYK présentée comme une valeur entière signée de 32 bits. Fournit une API similaire à la structure CmykColor. Elle est plus légère car la couleur CMYK est présentée simplement comme un Int32 plutôt que comme une structure avec des champs internes. Veuillez privilégier l'utilisation des méthodes statiques de cette classe lorsque cela est possible, au lieu de la structure CmykColor obsolète."
type: docs
weight: 280
url: /fr/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

Méthodes d'aide pour travailler avec la couleur CMYK présentée comme une valeur entière signée de 32 bits. Fournit une API similaire à la structure [`CmykColor`](../cmykcolor/). Elle est plus légère car la couleur CMYK est présentée simplement comme un Int32 plutôt que comme une structure avec des champs internes. Veuillez privilégier l'utilisation des méthodes statiques de cette classe lorsque cela est possible, au lieu de la structure [`CmykColor`](../cmykcolor/) obsolète.

```csharp
public static class CmykColorHelper
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Crée un CMYK à partir de valeurs cyan, magenta, jaune et noir sur 32 bits. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Obtient la valeur du composant cyan. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Obtient la valeur du composant noir. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Obtient la valeur du composant magenta. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Obtient la valeur du composant jaune. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | La conversion d'une couleur CMYK en couleur ARGB. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | La conversion de couleurs CMYK en couleurs ARGB. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | La conversion de couleurs CMYK en couleurs ARGB. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion ICC avec les profils par défaut. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion ICC avec les profils par défaut. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion ICC avec un profil personnalisé. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion ICC avec des profils personnalisés. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | La conversion d'une couleur ARGB en couleur CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | La conversion de couleurs ARGB en couleurs CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | La conversion d'une couleur ARGB en couleur CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | La conversion de couleurs ARGB en couleurs CMYK. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Convertit le RGB en CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | La conversion de la couleur ARGB en couleur CMYK à l'aide de la conversion Icc avec les profils par défaut. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | La conversion des couleurs ARGB en couleurs CMYK à l'aide de la conversion Icc avec les profils par défaut. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | La conversion de la couleur ARGB en couleur CMYK à l'aide de la conversion Icc avec des profils personnalisés. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | La conversion des couleurs ARGB en couleurs CMYK à l'aide de la conversion Icc avec des profils personnalisés. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Convertit le RGB en CMYK en utilisant des profils ICC personnalisés. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


