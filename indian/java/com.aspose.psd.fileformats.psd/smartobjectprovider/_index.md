---
title: "SmartObjectProvider"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "स्मार्ट ऑब्जेक्ट प्रोवाइडर को परिभाषित करता है जो PSD फ़ाइल के ग्लोबल लिंक संसाधनों और उनकी सामग्री से डेटा स्रोतों को प्राप्त / सेट करने की सुविधा देता है।"
type: docs
weight: 17
url: /hi/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

स्मार्ट ऑब्जेक्ट प्रोवाइडर को परिभाषित करता है जो PSD फ़ाइल के ग्लोबल लिंक संसाधनों और उनकी सामग्री से डेटा स्रोतों को प्राप्त / सेट करने की सुविधा देता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | लेयर्स को एम्बेडेड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है। |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | लेयर्स को एम्बेडेड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है। |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | एक नई इंस्टेंस को इनिशियलाइज़ करता है [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) क्लास की। |
| [embedAllLinked()](#embedAllLinked--) | इमेज में सभी लिंक्ड स्मार्ट ऑब्जेक्ट्स को एम्बेड करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | स्मार्ट ऑब्जेक्ट लेयर कंटेंट का प्रकार प्राप्त करता है। |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | एम्बेडेड या लिंक्ड फ़ाइल सामग्री प्राप्त करता है। |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | यूनिक आईडी द्वारा लिंक डेटा स्रोत प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | सामग्री लोड करता है। |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | स्रोत लेयर को कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | प्रदान किए गए वैध GUIDs की सूची में न मौजूद एम्बेडेड और एक्सटर्नल रिसोर्सेज़ से डेटा स्रोतों को हटाता है। |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | प्रदान की गई सामग्री के साथ एम्बेड करने के लिए ग्लोबल रिसोर्सेज़ में डेटा स्रोत को बदलता है। |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | एक ग्लोबल LinkResource रिसोर्स में डेटा स्रोत को बाहरी फ़ाइल से निर्मित नए डेटा स्रोत के साथ बदलता है। |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | एम्बेडेड या एक्सटर्नल फ़ाइल सामग्री सेट करता है। |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | ग्लोबल लिंक रिसोर्स में लिंक डेटा स्रोत को सेट (बदलता या जोड़ता) करता है। |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | इमेज में सभी संशोधित स्मार्ट ऑब्जेक्ट्स की सामग्री को अपडेट करता है। |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | कंटेनर के भीतर सभी स्मार्ट ऑब्जेक्ट लेयर्स को अपडेट करता है जिनका  UniqueId  oldGuid से मेल खाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


लेयर्स को एम्बेडेड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | लेयर्स। |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


लेयर्स को एम्बेडेड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerNumbers | int[] | लेयर नंबर। |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


एक नई इंस्टेंस को इनिशियलाइज़ करता है [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) क्लास की।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | कंटेनर। |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


इमेज में सभी लिंक्ड स्मार्ट ऑब्जेक्ट्स को एम्बेड करता है।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


स्मार्ट ऑब्जेक्ट लेयर कंटेंट का प्रकार प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | अद्वितीय पहचानकर्ता। |

**Returns:**
int - स्मार्ट ऑब्जेक्ट लेयर कंटेंट का प्रकार।
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


एम्बेडेड या लिंक्ड फ़ाइल सामग्री प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | लिंक डेटा स्रोत का अद्वितीय पहचानकर्ता। |

**Returns:**
byte[] - byte[] सामग्री।
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


यूनिक आईडी द्वारा लिंक डेटा स्रोत प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | अद्वितीय पहचानकर्ता। |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


सामग्री लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | अद्वितीय पहचानकर्ता। |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | लोड विकल्प। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


स्रोत लेयर को कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | स्रोत लेयर। |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


प्रदान की गई वैध GUIDs की सूची में न मौजूद एम्बेडेड और बाहरी संसाधनों से डेटा स्रोतों को हटाता है। यह मेथड वर्तमान वैध डेटा स्रोत पहचानकर्ताओं की तुलना करके अनाथ डेटा स्रोतों को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | रखने के लिए वैध डेटा स्रोत GUIDs की सूची। इस सूची में नहीं होने वाले डेटा स्रोत हटाए जाएंगे। |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


प्रदान की गई सामग्री के साथ एम्बेड करने के लिए ग्लोबल रिसोर्सेज़ में डेटा स्रोत को बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | मौजूदा डेटा स्रोत का अद्वितीय पहचानकर्ता। |
| contents | byte[] | नए डेटा स्रोत के लिए डेटा। |

**Returns:**
com.aspose.ms.System.Guid - निर्मित एम्बेडेड डेटा स्रोत का अद्वितीय पहचानकर्ता।  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


एक ग्लोबल LinkResource रिसोर्स में डेटा स्रोत को बाहरी फ़ाइल से निर्मित नए डेटा स्रोत के साथ बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | स्थापित संसाधन। |
| linkedPath | java.lang.String | लिंक्ड फ़ाइल का पूर्ण पथ। |
| isReplaceOnlyThis | boolean | यदि true है, तो ग्लोबल संसाधनों में डेटा स्रोत को न हटाएँ। |

**Returns:**
com.aspose.ms.System.Guid - निर्मित लिंक्ड डेटा स्रोत का अद्वितीय पहचानकर्ता Guid। [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


एम्बेडेड या एक्सटर्नल फ़ाइल सामग्री सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | लिंक डेटा स्रोत का अद्वितीय पहचानकर्ता। |
| डेटा | byte[] | डेटा। |
| fileType | java.lang.String | डेटा फ़ाइल प्रकार। |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


ग्लोबल लिंक रिसोर्स में लिंक डेटा स्रोत को सेट (बदलता या जोड़ता) करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | लिंक डेटा स्रोत। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


इमेज में सभी संशोधित स्मार्ट ऑब्जेक्ट्स की सामग्री को अपडेट करता है।

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


कंटेनर के भीतर सभी स्मार्ट ऑब्जेक्ट लेयर्स को अपडेट करता है जिनका UniqueId oldGuid से मेल खाता है। मेल खाने वाले लेयर्स का UniqueId newGuid को पुनः सौंपा जाता है और उनकी सामग्री को रीफ़्रेश किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | बदलने के लिए मूल स्मार्ट ऑब्जेक्ट डेटा स्रोत का अद्वितीय पहचानकर्ता। |
| newGuid | com.aspose.ms.System.Guid | नए स्मार्ट ऑब्जेक्ट डेटा स्रोत को सौंपने के लिए अद्वितीय पहचानकर्ता। |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | सामग्री को अपडेट करते समय लागू करने के लिए रिज़ॉल्यूशन सेटिंग्स। यदि null हो, तो छवि का रिज़ॉल्यूशन उपयोग किया जाता है। |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

