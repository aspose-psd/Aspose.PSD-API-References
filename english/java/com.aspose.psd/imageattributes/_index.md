---
title: ImageAttributes
second_title: Aspose.PSD for Java API Reference
description: An com.aspose.psd.ImageAttributes object contains information about how bitmap and metafile colors are manipulated during rendering.
type: docs
weight: 55
url: /java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

An  com.aspose.psd.ImageAttributes  object contains information about how bitmap and metafile colors are manipulated during rendering. An  com.aspose.psd.ImageAttributes  object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an  com.aspose.psd.ImageAttributes  object and pass the path of that  com.aspose.psd.ImageAttributes  object (along with the path of an [Image](../../com.aspose.psd/image)) to the drawImage method.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initializes a new instance of the  com.aspose.psd.ImageAttributes  class. |
## Fields

| Field | Description |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | The GDI image attributes. |
## Methods

| Method | Description |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Clears the brush color-remap table of this  com.aspose.psd.ImageAttributes  object. |
| [clearColorKey()](#clearColorKey--) | Clears the color key (transparency range) for the default category. |
| [clearColorKey(int type)](#clearColorKey-int-) | Clears the color key (transparency range) for a specified category. |
| [clearColorMatrix()](#clearColorMatrix--) | Clears the color-adjustment matrix for the default category. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Clears the color-adjustment matrix for a specified category. |
| [clearGamma()](#clearGamma--) | Disables gamma correction for the default category. |
| [clearGamma(int type)](#clearGamma-int-) | Disables gamma correction for a specified category. |
| [clearNoOp()](#clearNoOp--) | Clears the NoOp setting for the default category. |
| [clearNoOp(int type)](#clearNoOp-int-) | Clears the NoOp setting for a specified category. |
| [clearOutputChannel()](#clearOutputChannel--) | Clears the CMYK (cyan-magenta-yellow-black) output channel setting for the default category. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Clears the (cyan-magenta-yellow-black) output channel setting for a specified category. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Clears the output channel color profile setting for the default category. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Clears the output channel color profile setting for a specified category. |
| [clearRemapTable()](#clearRemapTable--) | Clears the color-remap table for the default category. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Clears the color-remap table for a specified category. |
| [clearThreshold()](#clearThreshold--) | Clears the threshold value for the default category. |
| [clearThreshold(int type)](#clearThreshold-int-) | Clears the threshold value for a specified category. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Sets the color-remap table for the brush category. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Sets the color key for the default category. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Sets the color key (transparency range) for a specified category. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Sets the color-adjustment matrix for the default category. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Sets the color-adjustment matrix for the default category. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Sets the color-adjustment matrix for a specified category. |
| [setGamma(float gamma)](#setGamma-float-) | Sets the gamma value for the default category. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Sets the gamma value for a specified category. |
| [setNoOp()](#setNoOp--) | Turns off color adjustment for the default category. |
| [setNoOp(int type)](#setNoOp-int-) | Turns off color adjustment for a specified category. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Sets the CMYK (cyan-magenta-yellow-black) output channel for the default category. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Sets the CMYK (cyan-magenta-yellow-black) output channel for a specified category. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Sets the output channel color-profile file for the default category. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Sets the output channel color-profile file for a specified category. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Sets the color-remap table for the default category. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Sets the color-remap table for a specified category. |
| [setThreshold(float threshold)](#setThreshold-float-) | Sets the threshold (transparency range) for the default category. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Sets the threshold (transparency range) for a specified category. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initializes a new instance of the  com.aspose.psd.ImageAttributes  class.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


The GDI image attributes.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Clears the brush color-remap table of this  com.aspose.psd.ImageAttributes  object.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Clears the color key (transparency range) for the default category.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Clears the color key (transparency range) for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the color key is cleared. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Clears the color-adjustment matrix for the default category.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Clears the color-adjustment matrix for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the color-adjustment matrix is cleared. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Disables gamma correction for the default category.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Disables gamma correction for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which gamma correction is disabled. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Clears the NoOp setting for the default category.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Clears the NoOp setting for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the NoOp setting is cleared. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Clears the CMYK (cyan-magenta-yellow-black) output channel setting for the default category.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Clears the (cyan-magenta-yellow-black) output channel setting for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the output channel setting is cleared. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Clears the output channel color profile setting for the default category.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Clears the output channel color profile setting for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the output channel profile setting is cleared. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Clears the color-remap table for the default category.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Clears the color-remap table for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the remap table is cleared. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Clears the threshold value for the default category.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Clears the threshold value for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the threshold is cleared. |

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Sets the color-remap table for the brush category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | An array of  com.aspose.psd.ColorMap  objects. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Sets the color key for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | The low color-key value. |
| colorHigh | [Color](../../com.aspose.psd/color) | The high color-key value. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Sets the color key (transparency range) for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | The low color-key value. |
| colorHigh | [Color](../../com.aspose.psd/color) | The high color-key value. |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the color key is set. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The color-adjustment matrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The grayscale-adjustment matrix. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The color-adjustment matrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The grayscale-adjustment matrix. |
| flags | int | An element of  Aspose.Imaging.ColorMatrixFlag  that specifies the type of image and color that will be affected by the color-adjustment and grayscale-adjustment matrices. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The color-adjustment matrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The grayscale-adjustment matrix. |
| mode | int | An element of  Aspose.Imaging.ColorMatrixFlag  that specifies the type of image and color that will be affected by the color-adjustment and grayscale-adjustment matrices. |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the color-adjustment and grayscale-adjustment matrices are set. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Sets the color-adjustment matrix for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The color-adjustment matrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Sets the color-adjustment matrix for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The color-adjustment matrix. |
| flags | int | An element of  Aspose.Imaging.ColorMatrixFlag  that specifies the type of image and color that will be affected by the color-adjustment matrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Sets the color-adjustment matrix for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | The color-adjustment matrix. |
| mode | int | An element of  Aspose.Imaging.ColorMatrixFlag  that specifies the type of image and color that will be affected by the color-adjustment matrix. |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the color-adjustment matrix is set. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Sets the gamma value for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gamma | float | The gamma correction value. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Sets the gamma value for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gamma | float | The gamma correction value. |
| type | int | An element of the  Aspose.Imaging.ColorAdjustType  enumeration that specifies the category for which the gamma value is set. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Turns off color adjustment for the default category.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Turns off color adjustment for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which color correction is turned off. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Sets the CMYK (cyan-magenta-yellow-black) output channel for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | int | An element of  Aspose.Imaging.ColorChannelFlag  that specifies the output channel. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Sets the CMYK (cyan-magenta-yellow-black) output channel for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | int | An element of  Aspose.Imaging.ColorChannelFlag  that specifies the output channel. |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the output channel is set. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Sets the output channel color-profile file for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | The path name of a color-profile file. If the color-profile file is in the %SystemRoot%\\System32\\Spool\\Drivers\\Color directory, this parameter can be the file name. Otherwise, this parameter must be the fully qualified path name. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Sets the output channel color-profile file for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | The path name of a color-profile file. If the color-profile file is in the %SystemRoot%\\System32\\Spool\\Drivers\\Color directory, this parameter can be the file name. Otherwise, this parameter must be the fully qualified path name. |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the output channel color-profile file is set. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Sets the color-remap table for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | An array of color pairs of type  com.aspose.psd.ColorMap . Each color pair contains an existing color (the first value) and the color that it will be mapped to (the second value). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Sets the color-remap table for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | An array of color pairs of type  com.aspose.psd.ColorMap . Each color pair contains an existing color (the first value) and the color that it will be mapped to (the second value). |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the color-remap table is set. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Sets the threshold (transparency range) for the default category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | A real number that specifies the threshold value. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Sets the threshold (transparency range) for a specified category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | A threshold value from 0.0 to 1.0 that is used as a breakpoint to sort colors that will be mapped to either a maximum or a minimum value. |
| type | int | An element of  Aspose.Imaging.ColorAdjustType  that specifies the category for which the color threshold is set. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | int | An element of  Aspose.Imaging.WrapMode  that specifies how repeated copies of an image are used to tile an area. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | int | An element of  Aspose.Imaging.WrapMode  that specifies how repeated copies of an image are used to tile an area. |
| color | [Color](../../com.aspose.psd/color) | An  com.aspose.psd.ImageAttributes  object that specifies the color of pixels outside of a rendered image. This color is visible if the mode parameter is set to  WrapMode.Clamp  and the source rectangle passed to DrawImage is larger than the image itself. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | int | An element of  Aspose.Imaging.WrapMode  that specifies how repeated copies of an image are used to tile an area. |
| color | [Color](../../com.aspose.psd/color) | A color object that specifies the color of pixels outside of a rendered image. This color is visible if the mode parameter is set to  WrapMode.Clamp  and the source rectangle passed to DrawImage is larger than the image itself. |
| clamp | boolean | This parameter has no effect. Set it to false. |

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

