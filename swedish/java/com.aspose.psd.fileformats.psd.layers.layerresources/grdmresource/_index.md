---
title: "GrdmResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Klass GrdmResource."
type: docs
weight: 35
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

Klassen GrdmResource. Innehåller information om Gradient-Map-lagret.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | Initierar en ny instans av klassen [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | Standardskalan. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB‑huvudversionen |
| [PsbResourceSignature](#PsbResourceSignature) | Den PSB‑specifika resurs‑signaturen. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD‑huvudversionen. |
| [ResourceSignature](#ResourceSignature) | Den gemensamma resurs‑signaturen. |
| [TypeToolKey](#TypeToolKey) | Nyckeln för typverktygsinformation. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Venture‑licensen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kontrollerar och sätter om resursen är PSB‑specifik. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Färgmodell. |
| [getColorPoints()](#getColorPoints--) | Hämtar eller anger färgpunkterna. |
| [getData()](#getData--) | Hämtar eller anger data. |
| [getDither()](#getDither--) | Är gradienten ditherad. |
| [getExpansionCount()](#getExpansionCount--) | Expansionsantal ( = 2 för Photoshop 6.0). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | Längd(= 32 för Photoshop 6.0) Ingen information om vad den ansvarar för. |
| [getGradientMode()](#getGradientMode--) | Läge för denna gradient bestämmer 'Gradient Type' = 'Solid/Noise' (0/1). |
| [getGradientName()](#getGradientName--) | Namn på gradienten: Unicode-sträng, utfylld. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getInterpolation()](#getInterpolation--) | Interpolering. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Hämtar eller anger interpolationsmetoden för gradienten. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getMaximumColor()](#getMaximumColor--) | Maximal färg för PixelDataFormat.Rgba64Bpp-formatet. |
| [getMinimumColor()](#getMinimumColor--) | Minimal färg för PixelDataFormat.Rgba64Bpp-formatet. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD-version som krävs för den här resursen. |
| [getReverse()](#getReverse--) | Är gradienten omvänd. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Det slumpmässiga talfröet som används för att generera färger för brusgradient. |
| [getRoughness()](#getRoughness--) | Roughness-faktor När 'Gradient type' = 'Noise' kan vi tilldela 'Roughness' (0 - 2048). |
| [getShowTransparency()](#getShowTransparency--) | Flagga för att visa transparens När 'Gradient type' = 'Noise' kan vi tilldela 'Add transparency' till true. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Hämtar eller anger transparenspunkterna. |
| [getUseVectorColor()](#getUseVectorColor--) | Flagga för att använda vektorfärg. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | Initierar längden på gradienten. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursdata till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setColorModel(short value)](#setColorModel-short-) | Färgmodell. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Hämtar eller anger färgpunkterna. |
| [setDither(boolean value)](#setDither-boolean-) | Är gradienten ditherad. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Expansionsantal ( = 2 för Photoshop 6.0). |
| [setGradientMode(int value)](#setGradientMode-int-) | Läge för denna gradient bestämmer 'Gradient Type' = 'Solid/Noise' (0/1). |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Namn på gradienten: Unicode-sträng, utfylld. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolering. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Hämtar eller anger interpolationsmetoden för gradienten. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Maximal färg för PixelDataFormat.Rgba64Bpp-formatet. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Minimal färg för PixelDataFormat.Rgba64Bpp-formatet. |
| [setReverse(boolean value)](#setReverse-boolean-) | Är gradienten omvänd. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Det slumpmässiga talfröet som används för att generera färger för brusgradient. |
| [setRoughness(int value)](#setRoughness-int-) | Roughness-faktor När 'Gradient type' = 'Noise' kan vi tilldela 'Roughness' (0 - 2048). |
| [setShowTransparency(short value)](#setShowTransparency-short-) | Flagga för att visa transparens När 'Gradient type' = 'Noise' kan vi tilldela 'Add transparency' till true. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Hämtar eller anger transparenspunkterna. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | Flagga för att använda vektorfärg. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
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


Initierar en ny instans av klassen [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdVersion | int | PSD-versionen för resursen. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


Standardskalan.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB‑huvudversionen

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Den PSB‑specifika resurs‑signaturen.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD‑huvudversionen.

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Den gemensamma resurs‑signaturen.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Nyckeln för typverktygsinformation.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Venture‑licensen.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Kontrollerar och anger om resursen är PSB-specifik. Vissa resurser känns inte igen för närvarande, men vi har en fullständig lista över PSB-specifika resurser som ändrar deras beteende vid sparning. Så vi måste åtminstone kontrollera detta i UnknownResource.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | int | Nyckeln. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Färgsmodell. När 'Gradient type' = 'Noise' kan vi tilldela 'Color Model' till RGB/SHB/LAB (3/4/6).

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Hämtar eller anger färgpunkterna.

Värde: färgpunkterna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


Hämtar eller anger data.

Värde: Data.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Är gradienten ditherad.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Expansionsantal ( = 2 för Photoshop 6.0).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


Längd(= 32 för Photoshop 6.0) Ingen information om vad den ansvarar för.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Läge för denna gradient bestämmer 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Namn på gradienten: Unicode-sträng, utfylld.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Hämtar eller anger rubriken.

Värde: Headern.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolation. Bestämmer släthet när 'Gradient Type' = 'Solid' (GradientMode = 0).

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Hämtar eller anger interpolationsmetoden för gradienten.

**Returns:**
long
### getKey() {#getKey--}
```
public final int getKey()
```


Hämtar lagrets resursnyckel.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Hämtar lagrets resurslängd i byte.

**Returns:**
int
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Maximal färg för PixelDataFormat.Rgba64Bpp-formatet. Färgen har ARGB-kanaler, varje kanal är 16-bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Minimal färg för PixelDataFormat.Rgba64Bpp-formatet. Färgen har ARGB-kanaler, varje kanal är 16-bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Hämtar prefixlängden. Standardvärdet är 12 för 8BIM-resurser och 16 för 8B64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdVersion | int | PSD-versionen. |

**Returns:**
int - Prefixlängden.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Hämtar den minsta PSD-version som krävs för den här resursen. Version 3 behövs när interpolationsmetoden lagras explicit.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Är gradienten omvänd.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Det slumpmässiga talfröet som används för att generera färger för brusgradient.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Roughness-faktor När 'Gradient type' = 'Noise' kan vi tilldela 'Roughness' (0 - 2048).

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


Flagga för att visa transparens När 'Gradient type' = 'Noise' kan vi tilldela 'Add transparency' till true.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Hämtar eller anger transparenspunkterna.

Värde: transparenspunkterna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


Flagga för att använda vektorfärg.

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


Initierar längden på gradienten. GradientLength är skrivskyddad, så den kan bara tilldelas en gång.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short | Värdet. |

### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Bestämmer om resursen är PSB‑specifik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | int | Resursnyckeln. |

**Returns:**
boolean - true om resursen är PSB-specifik; annars false.
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs.

Värde: true om detta objekt är PSB-specifik resurs; annars false.

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


Sparar resursdata till den angivna strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| psdVersion | int | PSD-versionen. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Sparar den anpassade resursrubriken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| signatur | int | Signaturen. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Sparar rubrikens signatur, identifierare och längd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| signatur | int | Signaturen. |
| isLengthLong | boolean | Om satt till true är längden lång. |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Färgsmodell. När 'Gradient type' = 'Noise' kan vi tilldela 'Color Model' till RGB/SHB/LAB (3/4/6).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Hämtar eller anger färgpunkterna.

Värde: färgpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Är gradienten ditherad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Expansionsantal ( = 2 för Photoshop 6.0).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Läge för denna gradient bestämmer 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Namn på gradienten: Unicode-sträng, utfylld.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Hämtar eller anger rubriken.

Värde: Headern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolation. Bestämmer släthet när 'Gradient Type' = 'Solid' (GradientMode = 0).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Hämtar eller anger interpolationsmetoden för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Maximal färg för PixelDataFormat.Rgba64Bpp-formatet. Färgen har ARGB-kanaler, varje kanal är 16-bit.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Minimal färg för PixelDataFormat.Rgba64Bpp-formatet. Färgen har ARGB-kanaler, varje kanal är 16-bit.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Är gradienten omvänd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Det slumpmässiga talfröet som används för att generera färger för brusgradient.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Roughness-faktor När 'Gradient type' = 'Noise' kan vi tilldela 'Roughness' (0 - 2048).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


Flagga för att visa transparens När 'Gradient type' = 'Noise' kan vi tilldela 'Add transparency' till true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Hämtar eller anger transparenspunkterna.

Värde: transparenspunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


Flagga för att använda vektorfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En String som representerar detta objekt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

