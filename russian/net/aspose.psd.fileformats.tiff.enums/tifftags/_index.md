---
title: "Перечисление TiffTags"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags enum. Перечисление тегов TIFF."
type: docs
weight: 4640
url: /ru/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

Перечисление тегов TIFF.

```csharp
public enum TiffTags
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| SubFileType | `254` | Дескриптор данных подфайла. |
| OsubfileType | `255` | [устарело в TIFF rev. 5.0] Тип данных в подфайле. |
| ImageWidth | `256` | Ширина изображения в пикселях. |
| ImageLength | `257` | Высота изображения в пикселях. |
| BitsPerSample | `258` | Биты на канал (образец). |
| Compression | `259` | Метод сжатия данных. |
| Photometric | `262` | Фотометрическая интерпретация. |
| Thresholding | `263` | [устарело в TIFF rev. 5.0] Пороговая обработка данных. |
| CellWidth | `264` | [устарело в TIFF rev. 5.0] Ширина матрицы дизеринга. |
| CellLength | `265` | [устарело в TIFF rev. 5.0] Высота матрицы дизеринга |
| FillOrder | `266` | Порядок данных внутри байта. |
| DocumentName | `269` | Имя документа, в котором находится изображение. |
| ImageDescription | `270` | Информация об изображении. |
| Make | `271` | Название производителя сканера. |
| Model | `272` | Название/номер модели сканера. |
| StripOffsets | `273` | Смещения к полосам данных. |
| Orientation | `274` | [устарело в TIFF rev. 5.0] Ориентация изображения. |
| SamplesPerPixel | `277` | Количество образцов на пиксель. |
| RowsPerStrip | `278` | Строк на полосу данных. |
| StripByteCounts | `279` | Количество байтов для полос. |
| MinSampleValue | `280` | [устарело в TIFF rev. 5.0] Минимальное значение образца. |
| MaxSampleValue | `281` | [устарело в TIFF rev. 5.0] Максимальное значение образца. |
| Xresolution | `282` | Пиксели/разрешение по оси X. |
| Yresolution | `283` | Пиксели/разрешение по оси Y. |
| PlanarConfig | `284` | Организация хранения. |
| PageName | `285` | Имя страницы, из которой взято изображение. |
| Xposition | `286` | Смещение по X страницы изображения слева. |
| Yposition | `287` | Смещение по Y страницы изображения слева. |
| FreeOffsets | `288` | [устарело в TIFF rev. 5.0] Смещение в байтах к свободному блоку. |
| FreeByteCounts | `289` | [устарело в TIFF rev. 5.0] Размеры свободных блоков. |
| GrayResponseUnit | `290` | [устарело в TIFF rev. 6.0] Точность кривой градаций серого. |
| GrayResponseCurve | `291` | [устарело в TIFF rev. 6.0] Кривая отклика градаций серого. |
| T4Options | `292` | TIFF 6.0 официальное имя-синоним для GROUP3OPTIONS. Параметры кодирования факса CCITT Group 3. 32 битовых флага. |
| T6Options | `293` | Параметры кодирования факса CCITT Group 4. 32 битовых флага. TIFF 6.0 официальное имя-синоним для GROUP4OPTIONS. |
| ResolutionUnit | `296` | Единицы разрешения. |
| PageNumber | `297` | Номера страниц многостраничного документа. |
| ColorResponseUnit | `300` | [устарело в TIFF rev. 6.0] Точность цветовой кривой. |
| TransferFunction | `301` | Информация о колориметрии. |
| Software | `305` | Имя &amp; выпуск. |
| DateTime | `306` | Дата и время создания. |
| Artist | `315` | Создатель изображения. |
| HostComputer | `316` | Устройство, на котором создано. |
| Predictor | `317` | Схема предсказания с LZW. |
| WhitePoint | `318` | Белая точка изображения. |
| PrimaryChromaticities | `319` | Основные хроматичности. |
| ColorMap | `320` | RGB‑карта для палитрового изображения. |
| HalftoneHints | `321` | Информация о светах и тенях. |
| TileWidth | `322` | Ширина тайла в пикселях. |
| TileLength | `323` | Высота тайла в пикселях. |
| TileOffsets | `324` | Смещения к тайлам данных. |
| TileByteCounts | `325` | Количество байтов для тайлов. |
| BadFaxLines | `326` | Строки с неверным количеством пикселей. |
| CleanFaxData | `327` | Информация о восстановленных строках. |
| ConsecutiveBadFaxLines | `328` | Максимальное количество последовательных плохих строк. |
| SubIfd | `330` | Дескрипторы подизображений. |
| InkSet | `332` | Чернила в разделённом изображении. |
| InkNames | `333` | ASCII‑имена чернил. |
| NumberOfInks | `334` | Количество чернил. |
| DotRange | `336` | Коды точек 0 % и 100 %. |
| TargetPrinter | `337` | Цель разделения. |
| ExtraSamples | `338` | Информация о дополнительных образцах. |
| SampleFormat | `339` | Формат образца данных. |
| SminSampleValue | `340` | Переменная MinSampleValue. |
| SmaxSampleValue | `341` | Переменная MaxSampleValue. |
| TransferRange | `342` | Переменная TransferRange |
| ClipPath | `343` | ClipPath. Введено после TIFF rev 6.0 в техническом примечании Adobe TIFF 2. |
| Xclippathunits | `344` | XClipPathUnits. Введено после TIFF rev 6.0 в техническом примечании Adobe TIFF 2. |
| Yclippathunits | `345` | YClipPathUnits. Введено после TIFF rev 6.0 в техническом примечании Adobe TIFF 2. |
| Indexed | `346` | Indexed. Введено после TIFF rev 6.0 в техническом примечании Adobe TIFF 3. |
| JpegTables | `347` | Поток таблицы JPEG. Введено после TIFF rev 6.0. |
| OpiProxy | `351` | OPI Proxy. Введено после TIFF rev 6.0 в техническом примечании Adobe TIFF. |
| JpegProc | `512` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Алгоритм обработки JPEG. |
| JpegInerchangeFormat | `513` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Указатель на маркер SOI. |
| JpegInterchangeFormatLength | `514` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Длина потока JFIF |
| JpegRestartInterval | `515` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Длина интервала перезапуска. |
| JpegLosslessPredictors | `517` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Предсказатель без потерь proc. |
| JpegPointTransform | `518` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Преобразование без потерь point. |
| JpegQTables | `519` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Смещения матрицы Q. |
| JpegDCtables | `520` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Смещения таблицы DCT. |
| JpegACtables | `521` | [устарело согласно Техническому примечанию #2, которое определяет пересмотренную схему JPEG-in-TIFF] Смещения коэффициентов AC. |
| YcbcrCoefficients | `529` | Преобразование RGB → YCbCr. |
| YcbcrSubSampling | `530` | Коэффициенты субдискретизации YCbCr. |
| YcbcrPositioning | `531` | Позиционирование субвыборки. |
| ReferenceBlackWhite | `532` | Информация о колориметрии. |
| XmlPacket | `700` | XML пакет. Введено после TIFF rev 6.0 в спецификации Adobe XMP, январь 2004 г. |
| OpiImageid | `32781` | OPI ImageID. Введено после TIFF rev 6.0 в техническом примечании Adobe TIFF. |
| Refpts | `32953` | Точки привязки изображения. Приватный тег, зарегистрированный в Island Graphics. |
| Copyright | `33432` | Строка авторского права. Этот тег указан в TIFF rev. 6.0 с неизвестным владельцем. |
| PhotoshopResources | `34377` | Ресурсы изображения Photoshop. |
| IccProfile | `34675` | Встроенный профиль устройства ICC |
| ExifIfdPointer | `34665` | Указатель на Exif IFD. |
| XPTitle | `40091` | Информация об изображении, используемая Windows Explorer. XPTitle игнорируется Windows Explorer, если существует тег ImageDescription. |
| XPComment | `40092` | Комментарий к изображению, используемый Windows Explorer. |
| XPAuthor | `40093` | Автор изображения, используемый Windows Explorer. XPAuthor игнорируется Windows Explorer, если существует тег Artist. |
| XPKeywords | `40094` | Ключевые слова изображения, используемые Windows Explorer. |
| XPSubject | `40095` | Тема изображения, используемая Windows Explorer. |

### См. также

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


