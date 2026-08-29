---
title: "IImageExporterDescriptor"
second_title: "Java용 Aspose.PSD API 참조"
description: "이미지 내보내기 설명자를 나타냅니다."
type: docs
weight: 122
url: /ko/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

이미지 내보내기 설명자를 나타냅니다. 내보내기 설명자는 각 내보내기 인스턴스를 메모리에 보관해야 하는 필요성과 멀티스레딩 문제를 해결하기 위해 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | 이미지 내보내기가 저장 옵션으로 지정된 이미지 형식으로 지정된 이미지를 내보낼 수 있는지 여부를 결정합니다. |
| [createInstance()](#createInstance--) | 새 내보내기 인스턴스를 생성합니다. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


이미지 내보내기가 저장 옵션으로 지정된 이미지 형식으로 지정된 이미지를 내보낼 수 있는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 내보낼 이미지. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 옵션 기반입니다. |

**Returns:**
boolean - 이 설명자로 생성된 내보내기가 지정된 이미지를 지정된 파일 형식으로 내보낼 수 있으면 true; 그렇지 않으면 false.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


새 내보내기 인스턴스를 생성합니다.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
