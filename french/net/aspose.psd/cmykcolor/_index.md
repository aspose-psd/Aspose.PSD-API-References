---
title: "Structure CmykColor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Structure Aspose.PSD.CmykColor. La couleur CMJN du pixel"
type: docs
weight: 270
url: /fr/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

La couleur CMYK du pixel.

```csharp
public struct CmykColor
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Obtient le vide. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Obtient la valeur du composant cyan de cette structure [`Color`](../color/). |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Obtient une valeur indiquant si cette structure [`Color`](../color/) est non initialisée. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Obtient la valeur du composant noir de cette structure [`Color`](../color/). |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Obtient la valeur du composant magenta de cette structure [`Color`](../color/). |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Obtient la valeur du composant jaune de cette structure [`Color`](../color/). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | Crée une structure `CmykColor` à partir de valeurs cyan, magenta, jaune et noir sur 32 bits. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`FromComponents`](../cmykcolorhelper/fromcomponents/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | La conversion de ARGB 32 bits vers CMYKColor. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Détermine si l'objet spécifié est égal à cette instance. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | Obtient le code de hachage. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | Obtient la valeur. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | La conversion de CMYKColor vers une couleur ARGB 32 bits en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToArgb32`](../cmykcolorhelper/toargb32/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | La conversion d'une couleur ARGB 32 bits vers CMYKColor. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | La conversion de CMYKColor vers Color. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | La conversion de CMYKColor vers Color en utilisant la conversion icc. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | La conversion de CMYKColor vers Color en utilisant la conversion icc. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


