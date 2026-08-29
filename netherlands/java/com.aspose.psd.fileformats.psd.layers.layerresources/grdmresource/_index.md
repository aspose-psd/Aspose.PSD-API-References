---
title: "GrdmResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Klasse GrdmResource."
type: docs
weight: 35
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

Klasse GrdmResource. Bevat informatie over Gradient-Map-laag.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | Initialiseert een nieuw exemplaar van de [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | De standaard schaal. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | De PSB-headerversie |
| [PsbResourceSignature](#PsbResourceSignature) | De PSB-specifieke resourcehandtekening. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | De PSD-headerversie |
| [ResourceSignature](#ResourceSignature) | De algemene resourcehandtekening. |
| [TypeToolKey](#TypeToolKey) | De typegereedschap-informatiesleutel. |
| [ventureLicense_internalized](#ventureLicense-internalized) | De venture-licentie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Controleert en stelt in of de resource PSB-specifiek is. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Kleurmodel. |
| [getColorPoints()](#getColorPoints--) | Haalt op of stelt de kleurpunten in. |
| [getData()](#getData--) | Haalt op of stelt de gegevens in. |
| [getDither()](#getDither--) | Is de gradient geditherd. |
| [getExpansionCount()](#getExpansionCount--) | Uitbreidingsaantal ( = 2 voor Photoshop 6.0). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | Lengte(= 32 voor Photoshop 6.0) Geen informatie waar het voor verantwoordelijk is. |
| [getGradientMode()](#getGradientMode--) | Modus voor deze gradient bepaalt 'Gradient Type' = 'Solid/Noise' (0/1). |
| [getGradientName()](#getGradientName--) | Naam van de gradient: Unicode‑string, opgevuld. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getInterpolation()](#getInterpolation--) | Interpolatie. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Haalt de interpolatiemethode voor de gradient op of stelt deze in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getMaximumColor()](#getMaximumColor--) | Maximumkleur van het PixelDataFormat.Rgba64Bpp‑formaat. |
| [getMinimumColor()](#getMinimumColor--) | Minimumkleur van het PixelDataFormat.Rgba64Bpp‑formaat. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Haalt de prefixlengte op. |
| [getPsdVersion()](#getPsdVersion--) | Haalt de minimale PSD‑versie op die vereist is voor deze resource. |
| [getReverse()](#getReverse--) | Is de gradient omgekeerd. |
| [getRndNumberSeed()](#getRndNumberSeed--) | De seed voor willekeurige getallen die wordt gebruikt om kleuren te genereren voor ruiskleurverloop. |
| [getRoughness()](#getRoughness--) | Ruwheidsfactor. Wanneer 'Gradient type' = 'Noise', kunnen we 'Roughness' (0 - 2048) toewijzen. |
| [getShowTransparency()](#getShowTransparency--) | Vlag voor het tonen van transparantie. Wanneer 'Gradient type' = 'Noise', kunnen we 'Add transparency' op true zetten. |
| [getSignature()](#getSignature--) | Haalt de laagresourcehandtekening op. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Haalt op of stelt de transparantiepunten in. |
| [getUseVectorColor()](#getUseVectorColor--) | Vlag voor het gebruiken van vectorkleur. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | Initialiseert de lengte van de gradient. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bepaalt of de resource PSB-specifiek is. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Slaat resource‑gegevens op in de opgegeven streamcontainer. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Slaat de aangepaste resource‑header op. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Slaat de headerhandtekening, identifier en lengte op. |
| [setColorModel(short value)](#setColorModel-short-) | Kleurmodel. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Haalt op of stelt de kleurpunten in. |
| [setDither(boolean value)](#setDither-boolean-) | Is de gradient geditherd. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Uitbreidingsaantal ( = 2 voor Photoshop 6.0). |
| [setGradientMode(int value)](#setGradientMode-int-) | Modus voor deze gradient bepaalt 'Gradient Type' = 'Solid/Noise' (0/1). |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Naam van de gradient: Unicode‑string, opgevuld. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolatie. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Haalt de interpolatiemethode voor de gradient op of stelt deze in. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Maximumkleur van het PixelDataFormat.Rgba64Bpp‑formaat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Minimumkleur van het PixelDataFormat.Rgba64Bpp‑formaat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Is de gradient omgekeerd. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | De seed voor willekeurige getallen die wordt gebruikt om kleuren te genereren voor ruiskleurverloop. |
| [setRoughness(int value)](#setRoughness-int-) | Ruwheidsfactor. Wanneer 'Gradient type' = 'Noise', kunnen we 'Roughness' (0 - 2048) toewijzen. |
| [setShowTransparency(short value)](#setShowTransparency-short-) | Vlag voor het tonen van transparantie. Wanneer 'Gradient type' = 'Noise', kunnen we 'Add transparency' op true zetten. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Haalt op of stelt de transparantiepunten in. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | Vlag voor het gebruiken van vectorkleur. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


Initialiseert een nieuw exemplaar van de [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| psdVersion | int | De PSD‑versie van de resource. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


De standaard schaal.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


De PSB-headerversie

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


De PSB-specifieke resourcehandtekening.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


De PSD-headerversie

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


De algemene resourcehandtekening.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


De typegereedschap-informatiesleutel.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


De venture-licentie.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Controleert en stelt in of de resource PSB‑specifiek is. Sommige resources worden momenteel niet herkend, maar we hebben een volledige lijst van PSB‑specifieke resources die hun gedrag bij het opslaan wijzigen. Dus moeten we dit ten minste in UnknownResource controleren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | int | De sleutel. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Kleurmodel. Wanneer 'Gradient type' = 'Noise', kunnen we 'Color Model' toewijzen aan RGB/SHB/LAB (3/4/6).

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Haalt op of stelt de kleurpunten in.

Waarde: De kleurpunten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


Haalt op of stelt de gegevens in.

Waarde: De gegevens.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Is de gradient geditherd.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Uitbreidingsaantal ( = 2 voor Photoshop 6.0).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


Lengte(= 32 voor Photoshop 6.0) Geen informatie waar het voor verantwoordelijk is.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Modus voor deze gradient bepaalt 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Naam van de gradient: Unicode‑string, opgevuld.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Haalt op of stelt de header in.

Waarde: de header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolatie. Bepaalt gladheid wanneer 'Gradient Type' = 'Solid' (GradientMode = 0).

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Haalt de interpolatiemethode voor de gradient op of stelt deze in.

**Returns:**
long
### getKey() {#getKey--}
```
public final int getKey()
```


Haalt de laagresource‑sleutel op.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Haalt de lengte van de laagresource in bytes op.

**Returns:**
int
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Maximumkleur van het PixelDataFormat.Rgba64Bpp‑formaat. Kleur heeft ARGB‑kanalen, elk kanaal is 16 bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Minimumkleur van het PixelDataFormat.Rgba64Bpp‑formaat. Kleur heeft ARGB‑kanalen, elk kanaal is 16 bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Haalt de prefixlengte op. Standaardwaarde is 12 voor 8BIM‑resources en 16 voor 8B64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| psdVersion | int | De PSD-versie. |

**Returns:**
int - De prefixlengte.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Haalt de minimale PSD‑versie op die vereist is voor deze resource. Versie 3 is nodig wanneer de interpolatiemethode expliciet wordt opgeslagen.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Is de gradient omgekeerd.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


De seed voor willekeurige getallen die wordt gebruikt om kleuren te genereren voor ruiskleurverloop.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Ruwheidsfactor. Wanneer 'Gradient type' = 'Noise', kunnen we 'Roughness' (0 - 2048) toewijzen.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


Vlag voor het tonen van transparantie. Wanneer 'Gradient type' = 'Noise', kunnen we 'Add transparency' op true zetten.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Haalt de laagresourcehandtekening op.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Haalt op of stelt de transparantiepunten in.

Waarde: De transparantiepunten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


Vlag voor het gebruiken van vectorkleur.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


Initialiseert de lengte van de gradient. GradientLength is alleen‑lezen, dus kan slechts één keer worden toegewezen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short | De waarde. |

### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Bepaalt of de resource PSB-specifiek is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | int | De resource‑sleutel. |

**Returns:**
boolean -  true  als de resource PSB‑specifiek is; anders,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is.

Waarde:  true  als deze instantie PSB‑specifieke resource is; anders,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Slaat resource‑gegevens op in de opgegeven streamcontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| psdVersion | int | De PSD-versie. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Slaat de aangepaste resource‑header op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| handtekening | int | De handtekening. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Slaat de headerhandtekening, identifier en lengte op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| handtekening | int | De handtekening. |
| isLengthLong | boolean | als ingesteld op  true  is de lengte lang. |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Kleurmodel. Wanneer 'Gradient type' = 'Noise', kunnen we 'Color Model' toewijzen aan RGB/SHB/LAB (3/4/6).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Haalt op of stelt de kleurpunten in.

Waarde: De kleurpunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Is de gradient geditherd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Uitbreidingsaantal ( = 2 voor Photoshop 6.0).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Modus voor deze gradient bepaalt 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Naam van de gradient: Unicode‑string, opgevuld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Haalt op of stelt de header in.

Waarde: de header.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolatie. Bepaalt gladheid wanneer 'Gradient Type' = 'Solid' (GradientMode = 0).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Haalt de interpolatiemethode voor de gradient op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Maximumkleur van het PixelDataFormat.Rgba64Bpp‑formaat. Kleur heeft ARGB‑kanalen, elk kanaal is 16 bit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Minimumkleur van het PixelDataFormat.Rgba64Bpp‑formaat. Kleur heeft ARGB‑kanalen, elk kanaal is 16 bit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Is de gradient omgekeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


De seed voor willekeurige getallen die wordt gebruikt om kleuren te genereren voor ruiskleurverloop.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Ruwheidsfactor. Wanneer 'Gradient type' = 'Noise', kunnen we 'Roughness' (0 - 2048) toewijzen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


Vlag voor het tonen van transparantie. Wanneer 'Gradient type' = 'Noise', kunnen we 'Add transparency' op true zetten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Haalt op of stelt de transparantiepunten in.

Waarde: De transparantiepunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


Vlag voor het gebruiken van vectorkleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een String die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een String die deze instantie vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

