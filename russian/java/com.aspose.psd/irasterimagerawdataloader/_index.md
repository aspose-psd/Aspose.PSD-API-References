---
title: "IRasterImageRawDataLoader"
second_title: "Aspose.PSD for Java API Справочник"
description: "Загрузчик необработанных данных растрового изображения."
type: docs
weight: 137
url: /ru/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

Загрузчик необработанных данных растрового изображения.
## Методы

| Метод | Описание |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Получает текущие настройки необработанных данных. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Возвращает значение, указывающее, поддерживается ли загрузка необработанных данных. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Загружает необработанные данные. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без конвертации.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Возвращает значение, указывающее, поддерживается ли загрузка необработанных данных.

**Returns:**
логический -  true  если загрузка необработанных данных поддерживается; иначе,  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Загружает необработанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник, из которого загружаются необработанные данные. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, если данные не в указанном формате, будет выполнено их преобразование. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Загрузчик необработанных данных. |

