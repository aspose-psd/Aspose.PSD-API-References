---
title: BlncResource
second_title: Aspose.PSD for Java API Reference
description: BlncResource class is a resource of Color Adjustment Layer.
type: docs
weight: 12
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlncResource extends AdjustmentLayerResource
```

BlncResource class is a resource of Color Adjustment Layer.
## Constructors

| Constructor | Description |
| --- | --- |
| [BlncResource()](#BlncResource--) | Initializes a new instance of the [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) class. |
## Fields

| Field | Description |
| --- | --- |
| [DataLength_internalized](#DataLength-internalized) | The expected data length. |
| [HighlightsCyanRedBalanceExceptionMessage_internalized](#HighlightsCyanRedBalanceExceptionMessage-internalized) | The highlights cyan red balance out of range exception message. |
| [HighlightsMagentaGreenBalanceExceptionMessage_internalized](#HighlightsMagentaGreenBalanceExceptionMessage-internalized) | The highlights magenta green balance out of range exception message |
| [HighlightsYellowBlueBalanceExceptionMessage_internalized](#HighlightsYellowBlueBalanceExceptionMessage-internalized) | The highlights yellow blue balance out of range exception message |
| [MidtonesCyanRedBalanceExceptionMessage_internalized](#MidtonesCyanRedBalanceExceptionMessage-internalized) | The midtones cyan red balance out of range exception message. |
| [MidtonesMagentaGreenBalanceExceptionMessage_internalized](#MidtonesMagentaGreenBalanceExceptionMessage-internalized) | The midtones magenta green balance out of range exception message. |
| [MidtonesYellowBlueBalanceExceptionMessage_internalized](#MidtonesYellowBlueBalanceExceptionMessage-internalized) | The midtones yellow blue balance out of range exception message. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | The PSB header version |
| [PsbResourceSignature](#PsbResourceSignature) | The PSB-specific resource signature. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | The PSD header version |
| [ResourceSignature](#ResourceSignature) | The common resource signature. |
| [ShadowsCyanRedBalanceExceptionMessage_internalized](#ShadowsCyanRedBalanceExceptionMessage-internalized) | The shadows cyan red balance out of range exception message. |
| [ShadowsMagentaGreenBalanceExceptionMessage_internalized](#ShadowsMagentaGreenBalanceExceptionMessage-internalized) | The shadows magenta green balance out of range exception message. |
| [ShadowsYellowBlueBalanceExceptionMessage_internalized](#ShadowsYellowBlueBalanceExceptionMessage-internalized) | The shadows yellow blue balance out of range exception message. |
| [TypeToolKey](#TypeToolKey) | The type tool info key. |
| [ventureLicense_internalized](#ventureLicense-internalized) | The venture license. |
## Methods

| Method | Description |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Gets or sets the data. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getHighlightsCyanRedBalance()](#getHighlightsCyanRedBalance--) | Gets or sets the Highlights Cyan Red Balance. |
| [getHighlightsMagentaGreenBalance()](#getHighlightsMagentaGreenBalance--) | Gets or sets the Highlights Magenta Green Balance. |
| [getHighlightsYellowBlueBalance()](#getHighlightsYellowBlueBalance--) | Gets or sets the Highlights Yellow Blue Balance. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getMidtonesCyanRedBalance()](#getMidtonesCyanRedBalance--) | Gets or sets the Midtones Cyan Red Balance. |
| [getMidtonesMagentaGreenBalance()](#getMidtonesMagentaGreenBalance--) | Gets or sets the Midtones Magenta Green Balance. |
| [getMidtonesYellowBlueBalance()](#getMidtonesYellowBlueBalance--) | Gets or sets the Midtones Yellow Blue Balance. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Gets or sets a value indicating whether this [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserves luminosity. |
| [getPsdVersion()](#getPsdVersion--) | Gets the PSD version. |
| [getShadowsCyanRedBalance()](#getShadowsCyanRedBalance--) | Gets or sets the Shadows Cyan Red Balance. |
| [getShadowsMagentaGreenBalance()](#getShadowsMagentaGreenBalance--) | Gets or sets the Shadows Magenta Green Balance. |
| [getShadowsYellowBlueBalance()](#getShadowsYellowBlueBalance--) | Gets or sets the Shadows Yellow Blue Balance. |
| [getSignature()](#getSignature--) | Gets the signature. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setHighlightsCyanRedBalance(short value)](#setHighlightsCyanRedBalance-short-) | Gets or sets the Highlights Cyan Red Balance. |
| [setHighlightsMagentaGreenBalance(short value)](#setHighlightsMagentaGreenBalance-short-) | Gets or sets the Highlights Magenta Green Balance. |
| [setHighlightsYellowBlueBalance(short value)](#setHighlightsYellowBlueBalance-short-) | Gets or sets the Highlights Yellow Blue Balance. |
| [setMidtonesCyanRedBalance(short value)](#setMidtonesCyanRedBalance-short-) | Gets or sets the Midtones Cyan Red Balance. |
| [setMidtonesMagentaGreenBalance(short value)](#setMidtonesMagentaGreenBalance-short-) | Gets or sets the Midtones Magenta Green Balance. |
| [setMidtonesYellowBlueBalance(short value)](#setMidtonesYellowBlueBalance-short-) | Gets or sets the Midtones Yellow Blue Balance. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Gets or sets a value indicating whether this [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserves luminosity. |
| [setShadowsCyanRedBalance(short value)](#setShadowsCyanRedBalance-short-) | Gets or sets the Shadows Cyan Red Balance. |
| [setShadowsMagentaGreenBalance(short value)](#setShadowsMagentaGreenBalance-short-) | Gets or sets the Shadows Magenta Green Balance. |
| [setShadowsYellowBlueBalance(short value)](#setShadowsYellowBlueBalance-short-) | Gets or sets the Shadows Yellow Blue Balance. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlncResource() {#BlncResource--}
```
public BlncResource()
```


Initializes a new instance of the [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) class.

### DataLength_internalized {#DataLength-internalized}
```
public static final int DataLength_internalized
```


The expected data length.

### HighlightsCyanRedBalanceExceptionMessage_internalized {#HighlightsCyanRedBalanceExceptionMessage-internalized}
```
public static final String HighlightsCyanRedBalanceExceptionMessage_internalized
```


The highlights cyan red balance out of range exception message.

### HighlightsMagentaGreenBalanceExceptionMessage_internalized {#HighlightsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String HighlightsMagentaGreenBalanceExceptionMessage_internalized
```


The highlights magenta green balance out of range exception message

### HighlightsYellowBlueBalanceExceptionMessage_internalized {#HighlightsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String HighlightsYellowBlueBalanceExceptionMessage_internalized
```


The highlights yellow blue balance out of range exception message

### MidtonesCyanRedBalanceExceptionMessage_internalized {#MidtonesCyanRedBalanceExceptionMessage-internalized}
```
public static final String MidtonesCyanRedBalanceExceptionMessage_internalized
```


The midtones cyan red balance out of range exception message.

### MidtonesMagentaGreenBalanceExceptionMessage_internalized {#MidtonesMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String MidtonesMagentaGreenBalanceExceptionMessage_internalized
```


The midtones magenta green balance out of range exception message.

### MidtonesYellowBlueBalanceExceptionMessage_internalized {#MidtonesYellowBlueBalanceExceptionMessage-internalized}
```
public static final String MidtonesYellowBlueBalanceExceptionMessage_internalized
```


The midtones yellow blue balance out of range exception message.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


The PSB header version

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


The PSB-specific resource signature.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


The PSD header version

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


The common resource signature.

### ShadowsCyanRedBalanceExceptionMessage_internalized {#ShadowsCyanRedBalanceExceptionMessage-internalized}
```
public static final String ShadowsCyanRedBalanceExceptionMessage_internalized
```


The shadows cyan red balance out of range exception message.

### ShadowsMagentaGreenBalanceExceptionMessage_internalized {#ShadowsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String ShadowsMagentaGreenBalanceExceptionMessage_internalized
```


The shadows magenta green balance out of range exception message.

### ShadowsYellowBlueBalanceExceptionMessage_internalized {#ShadowsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String ShadowsYellowBlueBalanceExceptionMessage_internalized
```


The shadows yellow blue balance out of range exception message.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


The type tool info key.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


The venture license.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Checks the and set if resource is PSB specific. Some resources are not recognized for now, but we have full list of PSB specific resources which changes their behaviour on save. So we need to check this in UnknownResource at least

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The key. |

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static BlncResource create_internalized(byte[] data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

**Returns:**
[BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
### getData() {#getData--}
```
public final byte[] getData()
```


Gets or sets the data.

Value: The data.

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Gets or sets the header.

Value: The header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHighlightsCyanRedBalance() {#getHighlightsCyanRedBalance--}
```
public final short getHighlightsCyanRedBalance()
```


Gets or sets the Highlights Cyan Red Balance.

Value: The Highlights Cyan Red Balance.

**Returns:**
short
### getHighlightsMagentaGreenBalance() {#getHighlightsMagentaGreenBalance--}
```
public final short getHighlightsMagentaGreenBalance()
```


Gets or sets the Highlights Magenta Green Balance.

Value: The Highlights Magenta Green Balance.

**Returns:**
short
### getHighlightsYellowBlueBalance() {#getHighlightsYellowBlueBalance--}
```
public final short getHighlightsYellowBlueBalance()
```


Gets or sets the Highlights Yellow Blue Balance.

Value: The Highlights Yellow Blue Balance.

**Returns:**
short
### getKey() {#getKey--}
```
public int getKey()
```


Gets the layer resource key.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Gets the layer resource length in bytes.

**Returns:**
int
### getMidtonesCyanRedBalance() {#getMidtonesCyanRedBalance--}
```
public final short getMidtonesCyanRedBalance()
```


Gets or sets the Midtones Cyan Red Balance.

Value: The Midtones Cyan Red Balance.

**Returns:**
short
### getMidtonesMagentaGreenBalance() {#getMidtonesMagentaGreenBalance--}
```
public final short getMidtonesMagentaGreenBalance()
```


Gets or sets the Midtones Magenta Green Balance.

Value: The Midtones Magenta Green Balance.

**Returns:**
short
### getMidtonesYellowBlueBalance() {#getMidtonesYellowBlueBalance--}
```
public final short getMidtonesYellowBlueBalance()
```


Gets or sets the Midtones Yellow Blue Balance.

Value: The Midtones Yellow Blue Balance.

**Returns:**
short
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Gets the prefix length. Default value is 12 for 8BIM resources. and 16 for 8B64

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| psdVersion | int | The PSD version. |

**Returns:**
int - The Prefix Length.
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


Gets or sets a value indicating whether this [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserves luminosity.

Value:  true  if it preserves luminosity; otherwise,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Gets the PSD version.

**Returns:**
int
### getShadowsCyanRedBalance() {#getShadowsCyanRedBalance--}
```
public final short getShadowsCyanRedBalance()
```


Gets or sets the Shadows Cyan Red Balance.

Value: The Shadows Cyan Red Balance.

**Returns:**
short
### getShadowsMagentaGreenBalance() {#getShadowsMagentaGreenBalance--}
```
public final short getShadowsMagentaGreenBalance()
```


Gets or sets the Shadows Magenta Green Balance.

Value: The Shadows Magenta Green Balance.

**Returns:**
short
### getShadowsYellowBlueBalance() {#getShadowsYellowBlueBalance--}
```
public final short getShadowsYellowBlueBalance()
```


Gets or sets the Shadows Yellow Blue Balance.

Value: The Shadows Yellow Blue Balance.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the signature.

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


Determines whether the resource is PSB specific.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The resource key. |

**Returns:**
boolean -  true  if the resource is PSB specific; otherwise,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Gets a value indicating whether this instance is resource PSB specific.

Value:  true  if this instance is resource PSB specific; otherwise,  false .

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


Saves the resource to the specified stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to save to. |
| psdVersion | int | The PSD version. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Saves the custom resource header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| signature | int | The signature. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Saves the header signature, identifier and length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| signature | int | The signature. |
| isLengthLong | boolean | if set to  true  length is long. |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Gets or sets the header.

Value: The header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHighlightsCyanRedBalance(short value) {#setHighlightsCyanRedBalance-short-}
```
public final void setHighlightsCyanRedBalance(short value)
```


Gets or sets the Highlights Cyan Red Balance.

Value: The Highlights Cyan Red Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setHighlightsMagentaGreenBalance(short value) {#setHighlightsMagentaGreenBalance-short-}
```
public final void setHighlightsMagentaGreenBalance(short value)
```


Gets or sets the Highlights Magenta Green Balance.

Value: The Highlights Magenta Green Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setHighlightsYellowBlueBalance(short value) {#setHighlightsYellowBlueBalance-short-}
```
public final void setHighlightsYellowBlueBalance(short value)
```


Gets or sets the Highlights Yellow Blue Balance.

Value: The Highlights Yellow Blue Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setMidtonesCyanRedBalance(short value) {#setMidtonesCyanRedBalance-short-}
```
public final void setMidtonesCyanRedBalance(short value)
```


Gets or sets the Midtones Cyan Red Balance.

Value: The Midtones Cyan Red Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setMidtonesMagentaGreenBalance(short value) {#setMidtonesMagentaGreenBalance-short-}
```
public final void setMidtonesMagentaGreenBalance(short value)
```


Gets or sets the Midtones Magenta Green Balance.

Value: The Midtones Magenta Green Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setMidtonesYellowBlueBalance(short value) {#setMidtonesYellowBlueBalance-short-}
```
public final void setMidtonesYellowBlueBalance(short value)
```


Gets or sets the Midtones Yellow Blue Balance.

Value: The Midtones Yellow Blue Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Gets or sets a value indicating whether this [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) preserves luminosity.

Value:  true  if it preserves luminosity; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShadowsCyanRedBalance(short value) {#setShadowsCyanRedBalance-short-}
```
public final void setShadowsCyanRedBalance(short value)
```


Gets or sets the Shadows Cyan Red Balance.

Value: The Shadows Cyan Red Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setShadowsMagentaGreenBalance(short value) {#setShadowsMagentaGreenBalance-short-}
```
public final void setShadowsMagentaGreenBalance(short value)
```


Gets or sets the Shadows Magenta Green Balance.

Value: The Shadows Magenta Green Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setShadowsYellowBlueBalance(short value) {#setShadowsYellowBlueBalance-short-}
```
public final void setShadowsYellowBlueBalance(short value)
```


Gets or sets the Shadows Yellow Blue Balance.

Value: The Shadows Yellow Blue Balance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

