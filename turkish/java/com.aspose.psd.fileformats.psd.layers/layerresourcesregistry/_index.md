---
title: "LayerResourcesRegistry"
second_title: "Java için Aspose.PSD API Referansı"
description: "Katman kaynakları kayıt defterini temsil eder."
type: docs
weight: 26
url: /tr/java/com.aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Inheritance:**
java.lang.Object
```
public final class LayerResourcesRegistry
```

Katman kaynakları kayıt defterini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LayerResourcesRegistry()](#LayerResourcesRegistry--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, int psdVersion)](#getFirstSupportedDescriptor-java.io.InputStream-int-) | İlk desteklenen açıcı tanımlayıcısını alır. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Tür adıyla ilk desteklenen tanımlayıcıyı alır. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Kayıtlı tanımlayıcıları alır. |
| [hashCode()](#hashCode--) |  |
| [loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-) | Belirtilen akış için uygun bulunan ilk açıcıyı kullanarak [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) yükler. |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerDefaultPsdOptions_internalized()](#registerDefaultPsdOptions-internalized--) | Varsayılan PSD seçeneklerini kaydeder. |
| [registerOpener(ILayerResourceLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | Açıcıyı kaydeder. |
| [registerPsdLoadOptions_internalized(PsdLoadOptions load)](#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-) | PSD yükleme seçeneklerini kaydeder. |
| [toString()](#toString--) |  |
| [unregisterOpener(ILayerResourceLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | Açıcı kaydını siler. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerResourcesRegistry() {#LayerResourcesRegistry--}
```
public LayerResourcesRegistry()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
### getFirstSupportedDescriptor(InputStream stream, int psdVersion) {#getFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


İlk desteklenen açıcı tanımlayıcısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Akış. |
|  | psdVersion | int | PSD sürümü. |

--------------------

İlk yükleyici aslında son kaydedilen olacaktır. |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static ILayerResourceLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Tür adıyla ilk desteklenen tanımlayıcıyı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Tanımlayıcı tür adı. |

--------------------

İlk açıcı tanımlayıcı aslında son kaydedilen olacaktır. |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static ILayerResourceLoader[] getRegisteredDescriptors()
```


Kayıtlı tanımlayıcıları alır.

Değer: Kayıtlı tanımlayıcılar.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


Belirtilen akış için uygun bulunan ilk açıcıyı kullanarak [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Akış. |
|  | psdVersion | int | PSD sürümü. |

--------------------

İlk açıcı aslında son kaydedilen olacaktır. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerDefaultPsdOptions_internalized() {#registerDefaultPsdOptions-internalized--}
```
public static void registerDefaultPsdOptions_internalized()
```


Varsayılan PSD seçeneklerini kaydeder.

### registerOpener(ILayerResourceLoader openerDescriptor) {#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void registerOpener(ILayerResourceLoader openerDescriptor)
```


Açıcıyı kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Kaydedilecek açıcı tanımlayıcı. |

### registerPsdLoadOptions_internalized(PsdLoadOptions load) {#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-}
```
public static void registerPsdLoadOptions_internalized(PsdLoadOptions load)
```


PSD yükleme seçeneklerini kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| load | [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) | Yükleme. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterOpener(ILayerResourceLoader openerDescriptor) {#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void unregisterOpener(ILayerResourceLoader openerDescriptor)
```


Açıcı kaydını siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Kaydı silinecek açıcı tanımlayıcı. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

