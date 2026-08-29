---
title: "PixelDataFormat"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le format des données pixel."
type: docs
weight: 80
url: /fr/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Le format de données de pixel. C'est un objet immuable.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet  System.Object  spécifié est égal à cette instance. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Obtient la couleur BGR avec un nombre spécifié de bits par échantillon. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient les bits par pixel. |
| [getCaption()](#getCaption--) | Obtient la légende du format de données de pixel. |
| [getChannelBits()](#getChannelBits--) | Obtient le nombre de bits pour chaque canal. |
| [getChannelsCount()](#getChannelsCount--) | Obtient le nombre de canaux. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Obtient la couleur CIE Lab avec un nombre spécifié de bits par échantillon. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | Obtient le  PixelDataFormat  défini pour 32 bits par pixel avec 8 bits pour chacun du cyan, magenta, jaune et noir. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon. |
| [getCmyk16()](#getCmyk16--) | Obtient le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 64 bits par pixel avec 16 bits pour chacun du cyan, magenta, jaune et noir. |
| [getCmyka()](#getCmyka--) | Obtient le acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Obtient la couleur CMYKA avec un nombre spécifié de bits par échantillon. |
| [getCmyka16()](#getCmyka16--) | Obtient le acmyk. |
| [getGrayscale()](#getGrayscale--) | Obtient le  PixelDataFormat  défini pour 8 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Obtient la couleur en niveaux de gris avec un nombre spécifié de bits par échantillon. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Obtient le  PixelDataFormat  défini pour 16 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255 et un composant alpha supplémentaire de 8 bits. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | Obtient le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 32 bits par pixel représentant l'intensité en niveaux de gris au format à virgule flottante. |
| [getPixelFormat()](#getPixelFormat--) | Obtient le format de pixel. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Obtient la couleur RGB avec un nombre spécifié de bits par échantillon. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Obtient la couleur RGB avec un nombre spécifié de bits par échantillon. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Obtient le  PixelDataFormat  défini pour 16 bits par pixel avec 5 bits pour chacun du rouge, vert et bleu, l'alpha n'est pas défini. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Obtient le  PixelDataFormat  défini pour 16 bits par pixel avec 5 bits pour le rouge, 6 bits pour le vert et 5 bits pour le bleu, l'alpha n'est pas défini. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Obtient le  PixelDataFormat  défini pour 24 bits par pixel avec 8 bits pour chacun de l'alpha, du rouge, du vert et du bleu, l'alpha n'est pas défini. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Obtient le  PixelDataFormat  défini pour 24 bits par pixel avec 8 bits pour chacun de l'alpha, du rouge, du vert et du bleu, l'alpha n'est pas défini. |
| [getRgb32Bpp()](#getRgb32Bpp--) | Obtient le  PixelDataFormat  défini pour 32 bits par pixel avec 8 bits pour chacun de l'alpha, du rouge, du vert et du bleu. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Obtient la couleur indexée BGRA avec un nombre spécifié de bits par échantillon. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Obtient le  PixelDataFormat  défini pour indexé 1 bit par couleur. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Obtient le  PixelDataFormat  défini pour indexé 2 bits par couleur. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Obtient le  PixelDataFormat  défini pour indexé 4 bits par couleur. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Obtient le  PixelDataFormat  défini pour indexé 8 bits par couleur. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Obtient le  PixelDataFormat  défini pour 32 bits par pixel avec 8 bits pour chacun de l'alpha, du rouge, du vert et du bleu. |
| [getRgba64Bpp()](#getRgba64Bpp--) | Obtient le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 64 bits par pixel avec 16 bits pour chacun des canaux alpha, rouge, vert et bleu. |
| [getYCbCr()](#getYCbCr--) | Obtient le  PixelDataFormat  défini pour 24 bits par pixel avec 8 bits pour chacun des composants chromatiques luma, différence de bleu et différence de rouge. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon. |
| [getYcck()](#getYcck--) | Obtient le  PixelDataFormat  défini pour 32 bits par pixel avec 8 bits pour chacun des composants chromatiques luma, différence de bleu, différence de rouge et noir. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Obtient la couleur YCCK avec un nombre spécifié de bits par échantillon. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [isIndexed_internalized()](#isIndexed-internalized--) | Obtient une valeur indiquant si cette instance est indexée. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Renvoie le résultat de l'égalité pour deux  PixelDataFormat  classes. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | Renvoie le résultat de la non-égalité pour deux  PixelDataFormat  classes. |
| [toString()](#toString--) | Retourne une  System.String  qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'objet  System.Object  spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le  System.Object  à comparer avec cette instance. |

**Returns:**
booléen -  true  si le  System.Object  spécifié est égal à cette instance ; sinon,  false .
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Obtient la couleur BGR avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient les bits par pixel.

**Returns:**
int - Le nombre de bits par pixel.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Obtient la légende du format de données de pixel.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Obtient le nombre de bits pour chaque canal.

**Returns:**
int[] - Les bits du canal.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Obtient le nombre de canaux.

**Returns:**
int - Le nombre de canaux.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Obtient la couleur CIE Lab avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerL | int | Le nombre de bits par canal L. |
| bitsPerA | int | Le nombre de bits par canal A. |
| bitsPerB | int | Le nombre de bits par canal B. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CIE Lab color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Obtient le  PixelDataFormat  défini pour 32 bits par pixel avec 8 bits pour chacun du cyan, magenta, jaune et noir.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerCyanChannel | int | Le nombre de bits par canal Cyan. |
| bitsPerMagentaChannel | int | Le nombre de bits par canal Magenta. |
| bitsPerYellowChannel | int | Le nombre de bits par canal Yellow. |
| bitsPerKeyChannel | int | Le nombre de bits par canal Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


Obtient le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 64 bits par pixel avec 16 bits pour chacun du cyan, magenta, jaune et noir.

Valeur : Le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 64 bits par pixel avec 16 bits pour chacun du cyan, magenta, jaune et noir.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Obtient le acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Obtient la couleur CMYKA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerCyanChannel | int | Le nombre de bits par canal Cyan. |
| bitsPerMagentaChannel | int | Le nombre de bits par canal Magenta. |
| bitsPerYellowChannel | int | Le nombre de bits par canal Yellow. |
| bitsPerKeyChannel | int | Le nombre de bits par canal Key. |
| bitsPerAlphaChannel | int | Le nombre de bits par canal Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


Obtient le acmyk.

Valeur : Le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 80 bits par pixel avec 16 bits pour chacun de l'alpha, du cyan, du magenta, du jaune et du noir.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


Obtient le  PixelDataFormat  défini pour 8 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Obtient la couleur en niveaux de gris avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Obtient le  PixelDataFormat  défini pour 16 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255 et un composant alpha supplémentaire de 8 bits.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |
| alphaChannelBits | int | Le nombre de bits par échantillon dans le canal alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


Obtient le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 32 bits par pixel représentant l'intensité en niveaux de gris au format à virgule flottante.

Valeur : Le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 32 bits par pixel représentant l'intensité en niveaux de gris au format virgule flottante

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtient le format de pixel.

**Returns:**
int - Le format de pixel.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Obtient la couleur RGB avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Obtient la couleur RGB avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerRedChannel | int | Le nombre de bits par canal Rouge. |
| bitsPerGreenChannel | int | Le nombre de bits par canal Vert. |
| bitsPerBlueChannel | int | Le nombre de bits par canal Bleu. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Obtient le  PixelDataFormat  défini pour 16 bits par pixel avec 5 bits pour chacun du rouge, vert et bleu, l'alpha n'est pas défini.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Obtient le  PixelDataFormat  défini pour 16 bits par pixel avec 5 bits pour le rouge, 6 bits pour le vert et 5 bits pour le bleu, l'alpha n'est pas défini.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Obtient le  PixelDataFormat  défini pour 24 bits par pixel avec 8 bits pour chacun de l'alpha, du rouge, du vert et du bleu, l'alpha n'est pas défini.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Obtient le  PixelDataFormat  défini pour 24 bits par pixel avec 8 bits pour chacun de l'alpha, du rouge, du vert et du bleu, l'alpha n'est pas défini.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Obtient le  PixelDataFormat  défini pour 32 bits par pixel avec 8 bits pour chacun de l'alpha, du rouge, du vert et du bleu.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Obtient la couleur indexée BGRA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Obtient le  PixelDataFormat  défini pour un format indexé de 1 bit par couleur. Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée. Utilisez avec prudence, car cela peut nécessiter une conversion d'une palette à une autre ou de RGBA vers un modèle de couleur indexé.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Obtient le  PixelDataFormat  défini pour un format indexé de 2 bits par couleur. Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée. Utilisez avec prudence, car cela peut nécessiter une conversion d'une palette à une autre ou de RGBA vers un modèle de couleur indexé.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Obtient le  PixelDataFormat  défini pour un format indexé de 4 bits par couleur. Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée. Utilisez avec prudence, car cela peut nécessiter une conversion d'une palette à une autre ou de RGBA vers un modèle de couleur indexé.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Obtient le  PixelDataFormat  défini pour un format indexé de 8 bits par couleur. Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée. Utilisez avec prudence, car cela peut nécessiter une conversion d'une palette à une autre ou de RGBA vers un modèle de couleur indexé.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerRedChannel | int | Le nombre de bits par canal Rouge. |
| bitsPerGreenChannel | int | Le nombre de bits par canal Vert. |
| bitsPerBlueChannel | int | Le nombre de bits par canal Bleu. |
| bitsPerAlphaChannel | int | Le nombre de bits par canal Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Obtient le  PixelDataFormat  défini pour 32 bits par pixel avec 8 bits pour chacun de l'alpha, du rouge, du vert et du bleu.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


Obtient le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 64 bits par pixel avec 16 bits pour chacun des canaux alpha, rouge, vert et bleu.

Valeur : Le [PixelDataFormat](../../com.aspose.psd/pixeldataformat) défini pour 64 bits par pixel avec 16 bits pour chacun de l'alpha, du rouge, du vert et du bleu.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Obtient le  PixelDataFormat  défini pour 24 bits par pixel avec 8 bits pour chacun des composants chromatiques luma, différence de bleu et différence de rouge.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerY | int | Le nombre de bits par canal Y. |
| bitsPerCb | int | Le nombre de bits par canal Cb |
| bitsPerCr | int | Le nombre de bits par canal Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Obtient le  PixelDataFormat  défini pour 32 bits par pixel avec 8 bits pour chacun des composants chromatiques luma, différence de bleu, différence de rouge et noir.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Obtient la couleur YCCK avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


Obtient une valeur indiquant si cette instance est indexée.

Valeur :  true  si cette instance est indexée ; sinon,  false .

**Returns:**
booléen - une valeur indiquant si cette instance est indexée.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| channelBits | int[] |  |
| pixelFormat | int |  |
| caption | java.lang.String |  |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Renvoie le résultat de l'égalité pour deux  PixelDataFormat  classes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Le premier  PixelDataFormat  à comparer. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Le deuxième  PixelDataFormat  à comparer. |

**Returns:**
booléen - Vrai si les deux  pixelFormat1  et  pixelFormat2  contiennent des données égales ou si les deux paramètres sont nuls.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Renvoie le résultat de la non-égalité pour deux  PixelDataFormat  classes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Le premier  PixelDataFormat  à comparer. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Le deuxième  PixelDataFormat  à comparer. |

**Returns:**
booléen - Vrai si les deux  pixelFormat1  et  pixelFormat2  contiennent des données différentes ou si l'un des paramètres est nul.
### toString() {#toString--}
```
public String toString()
```


Retourne une  System.String  qui représente cette instance.

**Returns:**
java.lang.String - Une System.String qui représente cette instance.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

