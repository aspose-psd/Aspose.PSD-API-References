---
title: "IRasterImageRawDataLoader"
second_title: "Java용 Aspose.PSD API 참조"
description: "래스터 이미지 원시 데이터 로더."
type: docs
weight: 137
url: /ko/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

래스터 이미지 원시 데이터 로더.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | 현재 원시 데이터 설정을 가져옵니다. |
| [isRawDataAvailable()](#isRawDataAvailable--) | 원시 데이터 로드가 지원되는지 여부를 나타내는 값을 가져옵니다. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | 원시 데이터를 로드합니다. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


현재 원시 데이터 설정을 가져옵니다. 이러한 설정을 사용할 때 데이터가 변환 없이 로드된다는 점에 유의하십시오.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


원시 데이터 로드가 지원되는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 원시 데이터 로드가 지원되면 true, 그렇지 않으면 false.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


원시 데이터를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 원시 데이터를 로드할 사각형. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | 로드된 데이터에 사용할 원시 데이터 설정. 지정된 형식이 아닌 경우 데이터 변환이 수행됩니다. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | 원시 데이터 로더. |

