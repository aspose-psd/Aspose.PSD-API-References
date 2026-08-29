---
title: "ImageExportersRegistry"
second_title: "Java용 Aspose.PSD API 참조"
description: "이미지 내보내기 레지스트리를 나타냅니다."
type: docs
weight: 57
url: /ko/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

이미지 내보내기 레지스트리를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | 지정된 저장 옵션 및 이미지에 적합한 첫 번째 찾은 내보내기자를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | 지정된 저장 옵션 및 이미지에 적합한 첫 번째 찾은 지원 설명자를 가져옵니다. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | 등록된 내보내기자 설명자를 가져옵니다. |
| [getRegisteredFormats()](#getRegisteredFormats--) | 등록된 내보내기 형식을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | 지정된 이미지 내보내기자 설명자를 등록합니다. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | 내보내기자를 등록합니다. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | 내보내기자 등록을 취소합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageExportersRegistry() {#ImageExportersRegistry--}
```
public ImageExportersRegistry()
```


### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


지정된 저장 옵션 및 이미지에 적합한 첫 번째 찾은 내보내기자를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 내보낼 이미지. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 내보내기에 사용할 저장 옵션. |

--------------------

첫 번째 내보내기자는 실제로 마지막에 등록된 것이 됩니다. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


지정된 저장 옵션 및 이미지에 적합한 첫 번째 찾은 지원 설명자를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 내보낼 이미지. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 옵션. |

--------------------

첫 번째 내보내기자 설명자는 실제로 마지막에 등록된 것이 됩니다. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


등록된 내보내기자 설명자를 가져옵니다.

값: 등록된 내보내기자 설명자.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


등록된 내보내기 형식을 가져옵니다.

값: 등록된 내보내기 형식.

**Returns:**
long
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




### register(IImageExporterDescriptor imageExporterDescriptor) {#register-com.aspose.psd.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor imageExporterDescriptor)
```


지정된 이미지 내보내기자 설명자를 등록합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | 이미지 내보내기자 설명자. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


내보내기자를 등록합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | 등록할 내보내기 설명자. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


내보내기자 등록을 취소합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | 등록 해제할 내보내기 설명자. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

