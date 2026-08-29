---
title: "VstkResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Resourceklasse VstkResource."
type: docs
weight: 14
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

Resource‑klasse VstkResource. Bevat informatie over Vector Stroke‑gegevens. De resource moet worden geïnitialiseerd via de AssignItems‑methode vanuit resourcedata, of door waarden toe te wijzen aan de eigenschappen van de klasse.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VstkResource()](#VstkResource--) | Initialiseert een nieuw exemplaar van de [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | De PSB-headerversie |
| [PsbResourceSignature](#PsbResourceSignature) | De PSB-specifieke resourcehandtekening. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | De PSD-headerversie |
| [ResourceSignature](#ResourceSignature) | De algemene resourcehandtekening. |
| [TypeToolKey](#TypeToolKey) | De typegereedschap-informatiesleutel. |
| [ventureLicense_internalized](#ventureLicense-internalized) | De venture-licentie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [assignItems_internalized(OSTypeStructure[] items)](#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Wijs items‑structuren toe vanuit Vstk‑resource. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Controleert en stelt in of de resource PSB-specifiek is. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Haalt een ClassID‑instantie op of stelt deze in. |
| [getClassName_internalized()](#getClassName-internalized--) | Haalt de klassenaam op of stelt deze in. |
| [getFillEnabled()](#getFillEnabled--) | Haalt een waarde op of stelt deze in die aangeeft of Stroke‑vulling is ingeschakeld. |
| [getFillSettings()](#getFillSettings--) | Haalt de vulinstellingen van de Stroke op of stelt ze in. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Haalt de prefixlengte op. |
| [getPsdVersion()](#getPsdVersion--) | Haalt de minimale PSD-versie op die vereist is voor de laagresource. |
| [getSignature()](#getSignature--) | Haalt de laagresourcehandtekening op. |
| [getStrokeEnabled()](#getStrokeEnabled--) | Haalt een waarde op of stelt deze in die aangeeft of stroke‑effect is ingeschakeld. |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | Haalt op of stelt de Stroke Blend-modus in. |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | Haalt op of stelt de Stroke-entiteit in. |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | Haalt de uitlijning van de Stroke‑stijllijn op of stelt deze in. |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | Haalt op of stelt het type van de stroke style line cap in. |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | Haalt op of stelt de breedte van de Stroke-lijnkap in. |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | Haalt op of stelt de dash-offset van de stroke style line in. |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | Haalt een array van lijndash‑patronen op of stelt deze in. |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | Haalt op of stelt het type van de stroke style line join in. |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | Haalt op of stelt de breedte van de Stroke-lijn in. |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | Haalt op of stelt de miter-limiet van de stroke style in. |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | Haalt op of stelt de opacity van de Stroke style in (0-100%). |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | Haalt op of stelt de resolutie van de Stroke style in. |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | Haalt op of stelt de schaalvergrendeling van de Stroke style in. |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | Haalt op of stelt de Stroke-aanpassing in. |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | Haalt op of stelt de versie van de stroke style in. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bepaalt of de resource PSB-specifiek is. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Slaat de resource op in de opgegeven streamcontainer. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Slaat de aangepaste resource‑header op. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Slaat de headerhandtekening, identifier en lengte op. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Haalt een ClassID‑instantie op of stelt deze in. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Haalt de klassenaam op of stelt deze in. |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of Stroke‑vulling is ingeschakeld. |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Haalt de vulinstellingen van de Stroke op of stelt ze in. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of stroke‑effect is ingeschakeld. |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | Haalt op of stelt de Stroke Blend-modus in. |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | Haalt op of stelt de Stroke-entiteit in. |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | Haalt de uitlijning van de Stroke‑stijllijn op of stelt deze in. |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | Haalt op of stelt het type van de stroke style line cap in. |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | Haalt op of stelt de breedte van de Stroke-lijnkap in. |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | Haalt op of stelt de dash-offset van de stroke style line in. |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | Haalt een array van lijndash‑patronen op of stelt deze in. |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | Haalt op of stelt het type van de stroke style line join in. |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | Haalt op of stelt de breedte van de Stroke-lijn in. |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | Haalt op of stelt de miter-limiet van de stroke style in. |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | Haalt op of stelt de opacity van de Stroke stryle in (0-100%). |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | Haalt op of stelt de resolutie van de Stroke style in. |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | Haalt op of stelt de schaalvergrendeling van de Stroke style in. |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | Haalt op of stelt de Stroke-aanpassing in. |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | Haalt op of stelt de versie van de stroke style in. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


Initialiseert een nieuw exemplaar van de [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) klasse.

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

### assignItems_internalized(OSTypeStructure[] items) {#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void assignItems_internalized(OSTypeStructure[] items)
```


Wijs items‑structuren toe vanuit Vstk‑resource.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| items | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Lijst met OSTypeStructure-instanties. |

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
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Haalt een ClassID‑instantie op of stelt deze in.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Haalt de klassenaam op of stelt deze in.

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


Haalt een waarde op of stelt deze in die aangeeft of Stroke‑vulling is ingeschakeld.

**Returns:**
boolean
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


Haalt de vulinstellingen van de Stroke op of stelt ze in.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Haalt op of stelt de header in.

Waarde: de header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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


Haalt de minimale PSD‑versie op die vereist is voor layer‑resource. 0 geeft geen beperkingen aan.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Haalt de laagresourcehandtekening op.

**Returns:**
int
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


Haalt een waarde op of stelt deze in die aangeeft of stroke‑effect is ingeschakeld.

**Returns:**
boolean
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


Haalt op of stelt de Stroke Blend-modus in.

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


Haalt op of stelt de Stroke-entiteit in. Eigenschap bepaalt de vullingsinstellingen van de stroke.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


Haalt de uitlijning van de Stroke‑stijllijn op of stelt deze in.

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


Haalt op of stelt het type van de stroke style line cap in.

Waarde: Het type van de stroke style line cap.

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


Haalt op of stelt de breedte van de Stroke-lijnkap in.

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


Haalt op of stelt de dash-offset van de stroke style line in.

Waarde: De dash-offset van de stroke style line.

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


Haalt een array van lijndash‑patronen op of stelt deze in.

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


Haalt op of stelt het type van de stroke style line join in.

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


Haalt op of stelt de breedte van de Stroke-lijn in.

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


Haalt op of stelt de miter-limiet van de stroke style in.

Waarde: De miter-limiet van de stroke style.

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


Haalt op of stelt de opacity van de Stroke style in (0-100%).

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


Haalt op of stelt de resolutie van de Stroke style in.

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


Haalt op of stelt de schaalvergrendeling van de Stroke style in.

**Returns:**
boolean
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


Haalt op of stelt de Stroke-aanpassing in.

**Returns:**
boolean
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


Haalt op of stelt de versie van de stroke style in.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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


Slaat de resource op in de opgegeven streamcontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer om naar op te slaan. |
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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Haalt een ClassID‑instantie op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Haalt de klassenaam op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of Stroke‑vulling is ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


Haalt de vulinstellingen van de Stroke op of stelt ze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of stroke‑effect is ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


Haalt op of stelt de Stroke Blend-modus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


Haalt op of stelt de Stroke-entiteit in. Eigenschap bepaalt de vullingsinstellingen van de stroke.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


Haalt de uitlijning van de Stroke‑stijllijn op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


Haalt op of stelt het type van de stroke style line cap in.

Waarde: Het type van de stroke style line cap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


Haalt op of stelt de breedte van de Stroke-lijnkap in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


Haalt op of stelt de dash-offset van de stroke style line in.

Waarde: De dash-offset van de stroke style line.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


Haalt een array van lijndash‑patronen op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


Haalt op of stelt het type van de stroke style line join in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


Haalt op of stelt de breedte van de Stroke-lijn in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


Haalt op of stelt de miter-limiet van de stroke style in.

Waarde: De miter-limiet van de stroke style.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


Haalt op of stelt de opacity van de Stroke stryle in (0-100%).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


Haalt op of stelt de resolutie van de Stroke style in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


Haalt op of stelt de schaalvergrendeling van de Stroke style in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


Haalt op of stelt de Stroke-aanpassing in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


Haalt op of stelt de versie van de stroke style in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

