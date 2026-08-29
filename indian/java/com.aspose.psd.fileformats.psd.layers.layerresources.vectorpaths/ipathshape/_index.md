---
title: "IPathShape"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "बेज़ियर वक्र के नोड्स से प्राप्त आकार।"
type: docs
weight: 31
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

बेज़ियर वक्र के नोड्स से प्राप्त आकार।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getItems()](#getItems--) | Bezier नॉट्स की सरणी प्राप्त करता है। |
| [getPathOperations()](#getPathOperations--) | पाथ शैप्स को संयोजित करने के लिए ऑपरेशन्स (बूलियन ऑपरेशन्स)। |
| [isClosed()](#isClosed--) | गुण प्राप्त करता या सेट करता है जो निर्धारित करता है कि आकार बंद है या नहीं। |
| [setClosed(boolean value)](#setClosed-boolean-) | गुण प्राप्त करता या सेट करता है जो निर्धारित करता है कि आकार बंद है या नहीं। |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Bexier नॉट्स की सरणी को असाइन करता है। |
| [setPathOperations(int value)](#setPathOperations-int-) | पाथ शैप्स को संयोजित करने के लिए ऑपरेशन्स (बूलियन ऑपरेशन्स)। |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Bezier नॉट्स की सरणी प्राप्त करता है।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord की सरणी।
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


पाथ शैप्स को संयोजित करने के लिए ऑपरेशन्स (बूलियन ऑपरेशन्स)।

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


गुण प्राप्त करता या सेट करता है जो निर्धारित करता है कि आकार बंद है या नहीं।

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


गुण प्राप्त करता या सेट करता है जो निर्धारित करता है कि आकार बंद है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Bexier नॉट्स की सरणी को असाइन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier नॉट्स की सरणी |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


पाथ शैप्स को संयोजित करने के लिए ऑपरेशन्स (बूलियन ऑपरेशन्स)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

