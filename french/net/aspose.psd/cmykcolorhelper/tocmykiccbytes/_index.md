---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode CmykColorHelper. Convertit le RGB en CMYK en utilisant des profils ICC personnalisés"
type: docs
weight: 120
url: /fr/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

Convertit le RGB en CMYK en utilisant des profils ICC personnalisés.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| startIndex | Int32 | L'index de départ de la couleur RGB. |
| longueur | Int32 | Le nombre de pixels RGB à convertir. |
| rgbIccStream | Stream | Le flux du profil RGB. |
| cmykIccStream | Stream | Le flux du profil CMYK. |

### Valeur de retour

Les couleurs CMYK présentées sous forme de tableau d'octets.

### Voir aussi

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


