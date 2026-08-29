---
title: "IImageExporter"
second_title: "Java용 Aspose.PSD API 참조"
description: "이미지 내보내기 도구입니다."
type: docs
weight: 121
url: /ko/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

이미지 내보내기 도구. 내부 Aspose.Imaging 형식의 데이터를 지정된 데이터 형식으로 내보낼 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | 지정된 이미지 데이터를 지정된 데이터 형식으로 내보냅니다. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | 지정된 이미지 데이터를 지정된 데이터 형식으로 내보냅니다. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


지정된 이미지 데이터를 지정된 데이터 형식으로 내보냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 내보낼 이미지 데이터. |
| stream | java.io.OutputStream | 데이터를 내보낼 스트림. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 이미지 내보내기 옵션 |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


지정된 이미지 데이터를 지정된 데이터 형식으로 내보냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 내보낼 이미지 데이터. |
| stream | java.io.OutputStream | 데이터를 내보낼 스트림. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 이미지 내보내기 옵션 |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 경계 사각형. |

