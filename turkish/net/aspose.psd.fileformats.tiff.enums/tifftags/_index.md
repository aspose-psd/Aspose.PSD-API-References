---
title: "Enum TiffTags"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags enum. TIFF etiketi enumu"
type: docs
weight: 4670
url: /tr/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

tiff etiket enumu.

```csharp
public enum TiffTags
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| SubFileType | `254` | Alt dosya veri tanımlayıcısı. |
| OsubfileType | `255` | [TIFF rev. 5.0 tarafından kullanımdan kaldırıldı] Alt dosyadaki veri türü. |
| ImageWidth | `256` | Görüntü genişliği piksel cinsinden. |
| ImageLength | `257` | Görüntü yüksekliği piksel cinsinden. |
| BitsPerSample | `258` | Kanal başına bit (örnek). |
| Compression | `259` | Veri sıkıştırma tekniği. |
| Photometric | `262` | Fotometrik yorumlama. |
| Thresholding | `263` | [TIFF rev. 5.0 tarafından kullanımdan kaldırıldı] Veride kullanılan eşikleme. |
| CellWidth | `264` | [TIFF rev. 5.0 tarafından kullanımdan kaldırıldı] Ditherleme matrisi genişliği. |
| CellLength | `265` | [TIFF rev. 5.0 tarafından kullanımdan kaldırıldı] Ditherleme matrisi yüksekliği |
| FillOrder | `266` | Bir bayt içindeki veri sırası. |
| DocumentName | `269` | Görüntüyü tutan belgenin adı. |
| ImageDescription | `270` | Görüntü hakkında bilgi. |
| Make | `271` | Tarayıcı üreticisinin adı. |
| Model | `272` | Tarayıcı model adı/numarası. |
| StripOffsets | `273` | Veri şeritlerine ofsetler. |
| Orientation | `274` | [TIFF rev. 5.0 ile kullanımdan kaldırıldı] Görüntü yönelimi. |
| SamplesPerPixel | `277` | Piksel başına örnek sayısı. |
| RowsPerStrip | `278` | Veri şeridi başına satır sayısı. |
| StripByteCounts | `279` | Şeritler için bayt sayısı. |
| MinSampleValue | `280` | [TIFF rev. 5.0 ile kullanımdan kaldırıldı] Minimum örnek değeri. |
| MaxSampleValue | `281` | [TIFF rev. 5.0 ile kullanımdan kaldırıldı] Maksimum örnek değeri. |
| Xresolution | `282` | X eksenindeki piksel/çözünürlük. |
| Yresolution | `283` | Y eksenindeki piksel/çözünürlük. |
| PlanarConfig | `284` | Depolama organizasyonu. |
| PageName | `285` | Görüntünün alındığı sayfanın adı. |
| Xposition | `286` | Görüntünün sol tarafındaki X sayfa ofseti. |
| Yposition | `287` | Görüntünün sol tarafındaki Y sayfa ofseti. |
| FreeOffsets | `288` | [TIFF rev. 5.0 ile kullanımdan kaldırıldı] Boş bloğa bayt ofseti. |
| FreeByteCounts | `289` | [TIFF rev. 5.0 ile kullanımdan kaldırıldı] Boş blokların boyutları. |
| GrayResponseUnit | `290` | [TIFF rev. 6.0 ile kullanımdan kaldırıldı] Gri ton eğrisi doğruluğu. |
| GrayResponseCurve | `291` | [TIFF rev. 6.0 ile kullanımdan kaldırıldı] Gri ton yanıt eğrisi. |
| T4Options | `292` | TIFF 6.0 için GROUP3OPTIONS takma adı. CCITT Group 3 faks kodlaması seçenekleri. 32 bayrak biti. |
| T6Options | `293` | CCITT Group 4 faks kodlaması seçenekleri. 32 bayrak biti. TIFF 6.0 için GROUP4OPTIONS takma adı. |
| ResolutionUnit | `296` | Çözünürlük birimleri. |
| PageNumber | `297` | Çok sayfalı sayfa numaraları. |
| ColorResponseUnit | `300` | [obsoleted by TIFF rev. 6.0] Renk eğrisi doğruluğu. |
| TransferFunction | `301` | Renk ölçümü bilgisi. |
| Software | `305` | Ad &amp; sürüm. |
| DateTime | `306` | Oluşturma tarihi ve saati. |
| Artist | `315` | Görüntünün oluşturucusu. |
| HostComputer | `316` | Oluşturulduğu makine. |
| Predictor | `317` | LZW ile tahmin şeması. |
| WhitePoint | `318` | Görüntü beyaz noktası. |
| PrimaryChromaticities | `319` | Birincil kromatik değerler. |
| ColorMap | `320` | Paletli görüntü için RGB haritası. |
| HalftoneHints | `321` | Vurgu + gölge bilgisi. |
| TileWidth | `322` | Döşeme genişliği piksel cinsinden. |
| TileLength | `323` | Döşeme yüksekliği piksel cinsinden. |
| TileOffsets | `324` | Veri döşemelerine ofsetler. |
| TileByteCounts | `325` | Döşemeler için bayt sayıları. |
| BadFaxLines | `326` | Yanlış piksel sayısına sahip satırlar. |
| CleanFaxData | `327` | Yeniden oluşturulmuş satır bilgisi. |
| ConsecutiveBadFaxLines | `328` | Maksimum ardışık hatalı satır. |
| SubIfd | `330` | Alt görüntü tanımlayıcıları. |
| InkSet | `332` | Ayrılmış görüntüdeki mürekkepler. |
| InkNames | `333` | Mürekkeplerin ASCII adları. |
| NumberOfInks | `334` | Mürekkep sayısı. |
| DotRange | `336` | %0 ve %100 nokta kodları. |
| TargetPrinter | `337` | Ayrım hedefi. |
| ExtraSamples | `338` | Ek örnekler hakkında bilgi. |
| SampleFormat | `339` | Veri örnek formatı. |
| SminSampleValue | `340` | Değişken MinSampleValue. |
| SmaxSampleValue | `341` | Değişken MaxSampleValue. |
| TransferRange | `342` | Değişken TransferRange |
| ClipPath | `343` | ClipPath. Adobe TIFF teknik notu 2 tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| Xclippathunits | `344` | XClipPathUnits. Adobe TIFF teknik notu 2 tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| Yclippathunits | `345` | YClipPathUnits. Adobe TIFF teknik notu 2 tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| Indexed | `346` | Indexed. Adobe TIFF Teknik Notu 3 tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| JpegTables | `347` | JPEG tablo akışı. TIFF rev 6.0 sonrası tanıtıldı. |
| OpiProxy | `351` | OPI Proxy. Adobe TIFF teknik notu tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| JpegProc | `512` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] JPEG işleme algoritması. |
| JpegInerchangeFormat | `513` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] SOI işaretleyicisine işaretçi. |
| JpegInterchangeFormatLength | `514` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] JFIF akış uzunluğu |
| JpegRestartInterval | `515` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] Yeniden başlatma aralığı uzunluğu. |
| JpegLosslessPredictors | `517` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] Kayıpsız işlem öngörücüsü. |
| JpegPointTransform | `518` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] Kayıpsız nokta dönüşümü. |
| JpegQTables | `519` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] Q matris ofsetleri. |
| JpegDCtables | `520` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] DCT tablo ofsetleri. |
| JpegACtables | `521` | [Technical Note #2 tarafından revize JPEG-in-TIFF şemasını belirten, kullanımdan kaldırıldı] AC katsayı ofsetleri. |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr dönüşümü. |
| YcbcrSubSampling | `530` | YCbCr alt örnekleme faktörleri. |
| YcbcrPositioning | `531` | Alt örnekleme konumlandırması. |
| ReferenceBlackWhite | `532` | Renk ölçümü bilgisi. |
| XmlPacket | `700` | XML paketi. Adobe XMP Specifikasyonu, Ocak 2004 tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| OpiImageid | `32781` | OPI ImageID. Adobe TIFF teknik notu tarafından TIFF rev 6.0 sonrası tanıtıldı. |
| Refpts | `32953` | Görüntü referans noktaları. Özel etiket Island Graphics'e kaydedildi. |
| Copyright | `33432` | Telif hakkı dizesi. Bu etiket TIFF rev. 6.0'da bilinmeyen sahiplikle listelenmiştir. |
| PhotoshopResources | `34377` | Photoshop görüntü kaynakları. |
| IccProfile | `34675` | Gömülü ICC cihaz profili |
| ExifIfdPointer | `34665` | Exif IFD'ye bir işaretçi. |
| XPTitle | `40091` | Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır. ImageDescription etiketi mevcutsa XPTitle Windows Explorer tarafından yok sayılır. |
| XPComment | `40092` | Görüntü yorumu, Windows Explorer tarafından kullanılır. |
| XPAuthor | `40093` | Görüntü Yazarı, Windows Explorer tarafından kullanılır. Artist etiketi mevcutsa XPAuthor Windows Explorer tarafından yok sayılır. |
| XPKeywords | `40094` | Görüntü Anahtar Kelimeleri, Windows Explorer tarafından kullanılır. |
| XPSubject | `40095` | Konu görüntüsü, Windows Explorer tarafından kullanılır. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


