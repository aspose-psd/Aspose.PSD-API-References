---
title: "CmykColorHelper.ToArgbIcc"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode CmykColorHelper. La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion ICC avec les profils par défaut"
type: docs
weight: 80
url: /fr/net/aspose.psd/cmykcolorhelper/toargbicc/
---
{{< psd/tize >}}
## ToArgbIcc(int[]) {#toargbicc_2}

La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion ICC avec les profils par défaut.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | Int32[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |

### Valeur de retour

Les couleurs ARGB.

### Voir aussi

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion ICC avec des profils personnalisés.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | Int32[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |
| cmykIccStream | Stream | Le flux contenant le profil Icc CMYK. |
| rgbIccStream | Stream | Le flux contenant le profil Icc RGB. |

### Valeur de retour

Les couleurs ARGB.

### Voir aussi

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int) {#toargbicc}

La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion ICC avec les profils par défaut.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | Int32 | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

### Valeur de retour

La couleur ARGB.

### Voir aussi

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion ICC avec un profil personnalisé.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | Int32 | La couleur CMYK présentée sous forme de valeur entière 32 bits. |
| cmykIccStream | Stream | Le flux contenant le profil Icc CMYK. |
| rgbIccStream | Stream | Le flux contenant le profil Icc RGB. |

### Valeur de retour

La couleur ARGB.

### Voir aussi

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


