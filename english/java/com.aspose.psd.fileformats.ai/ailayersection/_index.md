---
title: AiLayerSection
second_title: Aspose.PSD for Java API Reference
description: The Ai format Layer Section
type: docs
weight: 15
url: /java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

The Ai format Layer Section
## Methods

| Method | Description |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Adds the raster image. |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Gets or sets the blue color component. |
| [getClass()](#getClass--) |  |
| [getColorNumber()](#getColorNumber--) | Gets or sets the color number. |
| [getData()](#getData--) | Gets the string data. |
| [getDimValue()](#getDimValue--) | Gets or sets the dim value as percentage. |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getGreen()](#getGreen--) | Gets or sets the green color component. |
| [getName()](#getName--) | Gets or sets the layer name. |
| [getRasterImages()](#getRasterImages--) | Gets the raster images. |
| [getRed()](#getRed--) | Gets or sets the red color component. |
| [getStream_internalized()](#getStream-internalized--) | Gets the inner stream |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Gets or sets a value indicating whether this layer is dimmed. |
| [isLocked()](#isLocked--) | Gets or sets a value indicating whether this layer is locked. |
| [isPreview()](#isPreview--) | Gets or sets a value indicating whether this layer is preview. |
| [isPrinted()](#isPrinted--) | Gets or sets a value indicating whether this layer is printed. |
| [isShown()](#isShown--) | Gets or sets a value indicating whether this layer is shown. |
| [isTemplate()](#isTemplate--) | Gets or sets a value indicating whether this layer is a template layer. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Gets or sets the blue color component. |
| [setColorNumber(int value)](#setColorNumber-int-) | Gets or sets the color number. |
| [setDimValue(int value)](#setDimValue-int-) | Gets or sets the dim value as percentage. |
| [setGreen(int value)](#setGreen-int-) | Gets or sets the green color component. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Gets or sets a value indicating whether this layer is dimmed. |
| [setLocked(boolean value)](#setLocked-boolean-) | Gets or sets a value indicating whether this layer is locked. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the layer name. |
| [setPreview(boolean value)](#setPreview-boolean-) | Gets or sets a value indicating whether this layer is preview. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Gets or sets a value indicating whether this layer is printed. |
| [setRed(int value)](#setRed-int-) | Gets or sets the red color component. |
| [setShown(boolean value)](#setShown-boolean-) | Gets or sets a value indicating whether this layer is shown. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Gets or sets a value indicating whether this layer is a template layer. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Adds the raster image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | The raster image. |

### close() {#close--}
```
public void close()
```


Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. This method simply call dispose method.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| properties | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes the current instance.

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Gets or sets the blue color component.

Value: The blue color component.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Gets or sets the color number. -1 is the custom color value from Red, Green, Blue properties. Specifies the layer\\u2019s color setting.

Value: The color number.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Gets the string data.

**Returns:**
java.lang.String - The string data of section
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Gets or sets the dim value as percentage. Reduces the intensity of linked images and bitmap images contained in the layer to the specified percentage.

Value: The dim value as percentage.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Gets or sets the green color component.

Value: The green color component.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Gets or sets the layer name. Specifies the name of the item as it appears in the Layers panel.

Value: The layer name.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Gets the raster images.

Value: The raster images.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Gets or sets the red color component.

Value: The red color component.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Gets the inner stream

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Gets or sets a value indicating whether this layer is dimmed. Reduces the intensity of linked images and bitmap images contained in the layer.

Value:  true  if this layer is dimmed; otherwise,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gets or sets a value indicating whether this layer is locked. Prevents changes to the item.

Value:  true  if this layer is locked; otherwise,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Gets or sets a value indicating whether this layer is preview. Displays the artwork contained in the layer in color instead of as outlines.

Value:  true  if this layer is preview; otherwise,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Gets or sets a value indicating whether this layer is printed. Makes the artwork contained in the layer printable if true.

Value:  true  if this layer is printed; otherwise,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Gets or sets a value indicating whether this layer is shown. Displays all artwork contained in the layer on the artboard if true.

Value:  true  if this layer is shown; otherwise,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Gets or sets a value indicating whether this layer is a template layer.

Value:  true  if this layer is a template; otherwise,  false .

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Gets or sets the blue color component.

Value: The blue color component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Gets or sets the color number. -1 is the custom color value from Red, Green, Blue properties. Specifies the layer\\u2019s color setting.

Value: The color number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Gets or sets the dim value as percentage. Reduces the intensity of linked images and bitmap images contained in the layer to the specified percentage.

Value: The dim value as percentage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Gets or sets the green color component.

Value: The green color component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Gets or sets a value indicating whether this layer is dimmed. Reduces the intensity of linked images and bitmap images contained in the layer.

Value:  true  if this layer is dimmed; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Gets or sets a value indicating whether this layer is locked. Prevents changes to the item.

Value:  true  if this layer is locked; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets the layer name. Specifies the name of the item as it appears in the Layers panel.

Value: The layer name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Gets or sets a value indicating whether this layer is preview. Displays the artwork contained in the layer in color instead of as outlines.

Value:  true  if this layer is preview; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Gets or sets a value indicating whether this layer is printed. Makes the artwork contained in the layer printable if true.

Value:  true  if this layer is printed; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Gets or sets the red color component.

Value: The red color component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Gets or sets a value indicating whether this layer is shown. Displays all artwork contained in the layer on the artboard if true.

Value:  true  if this layer is shown; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Gets or sets a value indicating whether this layer is a template layer.

Value:  true  if this layer is a template; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

