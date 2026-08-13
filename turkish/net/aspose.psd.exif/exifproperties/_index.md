---
title: "Enum ExifProperties"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Exif.ExifProperties enum. Exif etiketleri listesi."
type: docs
weight: 1010
url: /tr/net/aspose.psd.exif/exifproperties/
---
{{< psd/tize >}}
## ExifProperties enumeration

Exif etiketleri listesi

```csharp
public enum ExifProperties : ushort
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| ImageWidth | `256` | Görüntü verisinin sütun sayısı, satır başına piksel sayısına eşittir. |
| ImageLength | `257` | Görüntü verisinin satır sayısı. |
| BitsPerSample | `258` | Görüntü bileşeni başına bit sayısı. Bu standartta görüntünün her bileşeni 8 bitten oluşur, bu nedenle bu etiketin değeri 8'dir. |
| Compression | `259` | Görüntü verisi için kullanılan sıkıştırma şeması. Birincil görüntü JPEG sıkıştırmalı olduğunda, bu belirleme gerekli değildir ve atlanır. |
| PhotometricInterpretation | `262` | Piksel bileşimi. |
| ImageDescription | `270` | Görüntünün başlığını veren bir karakter dizisi. "1988 şirket pikniği" gibi bir yorum olabilir. |
| Make | `271` | Kayıt ekipmanının üreticisi. Bu, görüntüyü oluşturan DSC, tarayıcı, video dijitalleştirici veya diğer ekipmanın üreticisidir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| Model | `272` | Ekipmanın model adı veya model numarası. Bu, görüntüyü oluşturan DSC, tarayıcı, video dijitalleştirici veya diğer ekipmanın model adı veya numarasıdır. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| Orientation | `274` | Satır ve sütun açısından görüntünün yönelimi. |
| SamplesPerPixel | `277` | Piksel başına bileşen sayısı. Bu standart RGB ve YCbCr görüntülere uygulandığından, bu etiket için ayarlanan değer 3'tür. |
| XResolution | `282` | ImageWidth yönünde ResolutionUnit başına piksel sayısı. Görüntü çözünürlüğü bilinmiyorsa, 72 [dpi] atanır. |
| YResolution | `283` | ImageLength yönünde ResolutionUnit başına piksel sayısı. XResolution ile aynı değer atanır. |
| PlanarConfiguration | `284` | Piksel bileşenlerinin chunky (parçalı) mı yoksa planar (düzlemsel) formatta mı kaydedildiğini gösterir. Bu alan yoksa, TIFF varsayılanı 1 (chunky) kabul edilir. |
| ResolutionUnit | `296` | XResolution ve YResolution ölçümü için birim. Hem XResolution hem de YResolution için aynı birim kullanılır. Görüntü çözünürlüğü bilinmiyorsa, 2 (inç) atanır. |
| TransferFunction | `301` | Görüntü için tablo biçiminde tanımlanan bir transfer fonksiyonu. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketinde belirtilir. |
| Software | `305` | Bu etiket, görüntüyü oluşturmak için kullanılan kamera veya görüntü giriş cihazının yazılım veya donanım sürümünün adını kaydeder. Ayrıntılı format belirtilmemiştir, ancak aşağıdaki örnek takip edilmelidir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| DateTime | `306` | Görüntünün oluşturulma tarihi ve saati. Exif standardında, dosyanın değiştirildiği tarih ve saat olarak kabul edilir. |
| Artist | `315` | Bu etiket, kamera sahibi, fotoğrafçı veya görüntü oluşturucusunun adını kaydeder. Ayrıntılı format belirtilmemiştir, ancak birlikte çalışabilirliği kolaylaştırmak için aşağıdaki örnek gibi yazılması önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. Ö.) "Kamera sahibi, John Smith; Fotoğrafçı, Michael Brown; Görüntü oluşturucu, Ken James" |
| WhitePoint | `318` | Görüntünün beyaz noktasının kromatikliği. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketinde belirtilir. |
| PrimaryChromaticities | `319` | Görüntünün üç ana renginin kromatikliği. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketinde belirtilir. |
| YCbCrCoefficients | `529` | RGB'den YCbCr görüntü verisine dönüşüm için matris katsayıları. |
| YCbCrSubSampling | `530` | Krominans bileşenlerinin parlaklık bileşenine göre örnekleme oranı. |
| YCbCrPositioning | `531` | Krominans bileşenlerinin parlaklık bileşenine göre konumu. Bu alan yalnızca JPEG sıkıştırmalı veri veya sıkıştırılmamış YCbCr veri için belirlenir. TIFF varsayılanı 1 (ortalanmış)dır; ancak Y:Cb:Cr = 4:2:2 olduğunda, bu standartta TV sistemlerinde görüntülendiğinde kaliteyi artırmak için veriyi kaydetmek üzere 2 (yan yana) kullanılmasını önerir. Bu alan mevcut değilse, okuyucu TIFF varsayılanını varsayar. Y:Cb:Cr = 4:2:0 durumunda, TIFF varsayılanı (ortalanmış) önerilir. Okuyucu her iki YCbCrPositioning tipini de destekleme yeteneğine sahip değilse, bu alandaki değere bakılmaksızın TIFF varsayılanını izlemelidir. Okuyucuların hem ortalanmış hem de yan yana konumlandırmayı destekleyebilmesi tercih edilir. |
| ReferenceBlackWhite | `532` | Referans siyah nokta değeri ve referans beyaz nokta değeri. TIFF'te varsayılanlar verilmez, ancak aşağıdaki değerler burada varsayılan olarak verilmiştir. Renk uzayı bir renk uzayı bilgi etiketi içinde bildirilir, varsayılan ise optimal görüntü özelliklerini veren değerdir Interoperability bu koşullar |
| Copyright | `33432` | Telif hakkı bilgisi. Bu standartta etiket, hem fotoğrafçı hem de editör telif haklarını göstermek için kullanılır. Görüntüye hak talep eden kişi veya kuruluşun telif hakkı bildirimidir. Interoperability telif hakkı beyanı tarih ve hakları içerecek şekilde bu alana yazılmalıdır; ör., "Copyright, John Smith, 19xx. All rights reserved.". Bu standartta alan, fotoğrafçı ve editör telif haklarını kaydeder, her biri beyanın ayrı bir bölümünde kaydedilir. Fotoğrafçı ve editör telif hakları arasında net bir ayrım olduğunda, bunlar fotoğrafçıdan sonra editör telif hakkı sırasıyla, NULL ile ayrılarak yazılır (bu durumda beyan aynı zamanda NULL ile bittiği için iki NULL kodu vardır). Yalnızca fotoğrafçı telif hakkı verildiğinde, bir NULL kodu ile sonlandırılır. Yalnızca editör telif hakkı verildiğinde, fotoğrafçı telif hakkı bölümü bir boşluk ve sonlandırıcı NULL kodundan oluşur, ardından editör telif hakkı verilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| ExposureTime | `33434` | Pozlama süresi, saniye cinsinden. |
| FNumber | `33437` | F numarası. |
| ExposureProgram | `34850` | Fotoğraf çekildiğinde pozlamayı ayarlamak için kamera tarafından kullanılan program sınıfı. |
| SpectralSensitivity | `34852` | Kullanılan kameranın her kanalının spektral duyarlılığını gösterir. |
| PhotographicSensitivity | `34855` | ISO 12232'de belirtildiği gibi kameranın veya giriş cihazının ISO Hızı ve ISO Enlemesini gösterir. |
| OECF | `34856` | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) gösterir. |
| ExifVersion | `36864` | Exif sürümü. |
| DateTimeOriginal | `36867` | Orijinal görüntü verisinin oluşturulduğu tarih ve saat. |
| DateTimeDigitized | `36868` | Dijitalleştirilen tarih ve saat. |
| ComponentsConfiguration | `37121` | Bileşen yapılandırması. |
| CompressedBitsPerPixel | `37122` | Sıkıştırılmış veriye özgüdür; piksel başına sıkıştırılmış bit sayısını belirtir. |
| ShutterSpeedValue | `37377` | Deklanşör hızı değeri. |
| ApertureValue | `37378` | Lens diyafram değeri. |
| BrightnessValue | `37379` | Parlaklık değeri. |
| ExposureBiasValue | `37380` | Pozlama sapması değeri. |
| MaxApertureValue | `37381` | Maksimum diyafram değeri. |
| SubjectDistance | `37382` | Konuya olan mesafe, metre cinsinden. |
| MeteringMode | `37383` | Ölçüm modu. |
| LightSource | `37384` | Işık kaynağı türü. |
| Flash | `37385` | Görüntü çekildiğinde flaş durumunu gösterir. |
| FocalLength | `37386` | Lensin gerçek odak uzaklığı, mm cinsinden. |
| SubjectArea | `37396` | Bu etiket, genel sahnedeki ana konunun konumunu ve alanını gösterir. |
| MakerNote | `37500` | Exif yazarları üreticilerinin istedikleri bilgileri kaydetmesi için bir etiket. İçerik üreticinin takdirine bağlıdır, ancak bu etiket yalnızca amaçlanan kullanım dışında kullanılmamalıdır. |
| UserComment | `37510` | Exif kullanıcılarının ImageDescription'daki anahtar kelimeler ve yorumların yanı sıra görüntüye anahtar kelimeler veya yorumlar yazabilmesi için bir etiket ve ImageDescription etiketinin karakter kodu sınırlamaları olmadan. |
| SubsecTime | `37520` | DateTime etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket. |
| SubsecTimeOriginal | `37521` | DateTimeOriginal etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket. |
| SubsecTimeDigitized | `37522` | DateTimeDigitized etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket. |
| FlashpixVersion | `40960` | Bir FPXR dosyası tarafından desteklenen Flashpix format sürümü. |
| ColorSpace | `40961` | Renk uzayı bilgi etiketi (ColorSpace) her zaman renk uzayı belirteci olarak kaydedilir. |
| RelatedSoundFile | `40964` | İlgili ses dosyası. |
| FlashEnergy | `41483` | Görüntü yakalandığında ölçülen Beam Candle Power Seconds (BCPS) cinsinden strob enerjisini gösterir. |
| SpatialFrequencyResponse | `41484` | Bu etiket, ISO 12233'te belirtildiği gibi, kamera veya giriş cihazının uzaysal frekans tablosu ve SFR değerlerini görüntü genişliği, görüntü yüksekliği ve diyagonal yönünde kaydeder. |
| FocalPlaneXResolution | `41486` | Kamera odak düzlemindeki FocalPlaneResolutionUnit başına görüntü genişliği (X) yönündeki piksel sayısını gösterir. |
| FocalPlaneYResolution | `41487` | Kamera odak düzlemindeki FocalPlaneResolutionUnit başına görüntü yüksekliği (Y) yönündeki piksel sayısını gösterir. |
| FocalPlaneResolutionUnit | `41488` | FocalPlaneXResolution ve FocalPlaneYResolution ölçümü için kullanılan birimi gösterir. Bu değer ResolutionUnit ile aynıdır. |
| SubjectLocation | `41492` | Sahnedeki ana konunun konumunu gösterir. Bu etiketin değeri, Rotation etiketiyle belirtilen döndürme işleminden önce, sol kenara göre ana konunun merkezindeki pikseli temsil eder. |
| ExposureIndex | `41493` | Görüntü yakalandığında kamera veya giriş cihazında seçilen pozlama indeksini gösterir. |
| SensingMethod | `41495` | Kamera veya giriş cihazındaki görüntü sensörü tipini gösterir. |
| FileSource | `41728` | Dosya kaynağı. |
| SceneType | `41729` | Sahne tipini gösterir. Eğer bir DSC görüntüyü kaydettiyse, bu etiket değeri her zaman 1 olarak ayarlanmalı ve görüntünün doğrudan fotoğraf çekildiğini gösterir. |
| CFAPattern | `41730` | Tek çipli renk alan sensörü kullanıldığında görüntü sensörünün renk filtre dizisi (CFA) geometrik desenini gösterir. Tüm algılama yöntemlerine uygulanmaz. |
| CustomRendered | `41985` | Bu etiket, çıktı odaklı render gibi görüntü verileri üzerinde özel işleme kullanımını gösterir. Özel işleme yapıldığında, okuyucunun daha fazla işleme devre dışı bırakması veya en aza indirmesi beklenir. |
| ExposureMode | `41986` | Bu etiket, görüntü çekildiğinde ayarlanan pozlama modunu gösterir. Otomatik bracketing modunda, kamera aynı sahnenin farklı pozlama ayarlarıyla bir dizi kare çeker. |
| WhiteBalance | `41987` | Bu etiket, görüntü çekildiğinde ayarlanan beyaz dengesi modunu gösterir. |
| DigitalZoomRatio | `41988` | Bu etiket, görüntü çekildiğinde dijital zoom oranını gösterir. Kaydedilen değerin payı 0 ise, dijital zoom kullanılmadığını gösterir. |
| FocalLengthIn35MmFilm | `41989` | Bu etiket, 35mm film kamera varsayımıyla eşdeğer odak uzaklığını milimetre cinsinden gösterir. 0 değeri odak uzaklığının bilinmediği anlamına gelir. Bu etiketin FocalLength etiketinden farklı olduğunu unutmayın. |
| SceneCaptureType | `41990` | Bu etiket, çekilen sahnenin tipini gösterir. Ayrıca görüntünün çekildiği modu kaydetmek için de kullanılabilir. |
| GainControl | `41991` | Bu etiket, genel görüntü kazancı ayarının derecesini gösterir. |
| Contrast | `41992` | Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan kontrast işleme yönünü gösterir. |
| Saturation | `41993` | Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan doygunluk işleme yönünü gösterir. |
| Sharpness | `41994` | Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan keskinlik işleme yönünü gösterir. |
| DeviceSettingDescription | `41995` | Bu etiket, belirli bir kamera modelinin fotoğraf çekim koşullarıyla ilgili bilgileri gösterir. Etiket yalnızca okuyucuda fotoğraf çekim koşullarını göstermek için kullanılır. |
| SubjectDistanceRange | `41996` | Bu etiket, nesneye olan mesafeyi gösterir. |
| ImageUniqueID | `42016` | Görselin benzersiz kimliği. |
| GPSVersionID | `0` | GPSInfoIFD sürümünü gösterir. |
| GPSLatitudeRef | `1` | Enlemin kuzey mi yoksa güney mi olduğunu gösterir. |
| GPSLatitude | `2` | Enlemi gösterir. Enlem, derece, dakika ve saniyeyi sırasıyla veren üç RATIONAL değer olarak ifade edilir. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik bir format dd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin dakikanın kesirli kısmı iki ondalık basamağa kadar verildiğinde, format dd/1,mmmm/100,0/1 olur. |
| GPSLongitudeRef | `3` | Boylamın doğu mu yoksa batı mı olduğunu gösterir. |
| GPSLongitude | `4` | Boylamı gösterir. Boylam, derece, dakika ve saniyeyi sırasıyla veren üç RATIONAL değer olarak ifade edilir. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik bir format ddd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin dakikanın kesirli kısmı iki ondalık basamağa kadar verildiğinde, format ddd/1,mmmm/100,0/1 olur. |
| GPSAltitudeRef | `5` | Referans irtifa olarak kullanılan yüksekliği gösterir. Referans deniz seviyesi ise ve irtifa deniz seviyesinin üzerindeyse, 0 verilir. İrtifa deniz seviyesinin altındaysa, 1 değeri verilir ve irtifa GPSAltitude etiketinde mutlak değer olarak gösterilir. |
| GPSAltitude | `6` | GPSAltitudeRef referansına göre yüksekliği gösterir. Yükseklik, tek bir RATIONAL değer olarak ifade edilir. Referans birimi metredir. |
| GPSTimestamp | `7` | Zamanı UTC (Eşgüdümlü Evrensel Zaman) olarak gösterir. TimeStamp saat, dakika ve saniyeyi veren üç RATIONAL değer olarak ifade edilir. |
| GPSSatellites | `8` | Ölçümler için kullanılan GPS uydularını gösterir. Bu etiket, uydu sayısı, kimlik numarası, yükselti açısı, azimut, SNR ve diğer bilgileri ASCII notasyonunda tanımlamak için kullanılabilir. Format belirtilmemiştir. GPS alıcısı ölçüm yapamıyorsa, etiket değeri NULL olarak ayarlanmalıdır. |
| GPSStatus | `9` | Görüntü kaydedildiğinde GPS alıcısının durumunu gösterir. |
| GPSMeasureMode | `10` | GPS ölçüm modunu gösterir. - 2- veya 3- boyutlu. |
| GPSDOP | `11` | GPS DOP (veri kesinlik derecesi) değerini gösterir. İki boyutlu ölçüm sırasında bir HDOP değeri, üç boyutlu ölçüm sırasında ise bir PDOP değeri yazılır. |
| GPSSpeedRef | `12` | GPS alıcısının hareket hızı birimini gösterir. 'K', 'M' ve 'N' sırasıyla kilometre/saat, mil/saat ve knot anlamına gelir. |
| GPSSpeed | `13` | GPS alıcısının hareket hızını gösterir. |
| GPSTrackRef | `14` | GPS alıcısının hareket yönü için referansı gösterir. 'T' gerçek yönü, 'M' manyetik yönü gösterir. |
| GPSTrack | `15` | GPS alıcısının hareket yönünü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır. |
| GPSImgDirectionRef | `16` | Çekildiği anda görüntünün yönü için referansı gösterir. 'T' gerçek yönü, 'M' manyetik yönü gösterir. |
| GPSImgDirection | `17` | Görüntünün çekildiği sıradaki yönünü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır. |
| GPSMapDatum | `18` | GPS alıcısı tarafından kullanılan jeodezik ölçüm verilerini gösterir. |
| GPSDestLatitudeRef | `19` | Hedef noktanın enleminin kuzey mi yoksa güney enlemi mi olduğunu gösterir. ASCII değeri 'N' kuzey enlemini, 'S' ise güney enlemini gösterir. |
| GPSDestLatitude | `20` | Hedef noktanın enlemini gösterir. Enlem, sırasıyla derece, dakika ve saniyeyi veren üç RATIONAL değer olarak ifade edilir. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik bir format dd/1,mm/1,ss/1 olur. Derece ve dakikalar kullanıldığında ve örneğin, dakikanın kesirli kısmı iki ondalık basamağa kadar verildiğinde, format dd/1,mmmm/100,0/1 olur. |
| GPSDestLongitudeRef | `21` | Hedef noktanın boylamının doğu mu yoksa batı boylamı mı olduğunu gösterir. ASCII 'E' doğu boylamını, 'W' ise batı boylamını gösterir. |
| GPSDestLongitude | `22` | Hedef noktanın boylamını gösterir. Boylam, sırasıyla derece, dakika ve saniyeyi veren üç RATIONAL değer olarak ifade edilir. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik bir format ddd/1,mm/1,ss/1 olur. Derece ve dakikalar kullanıldığında ve örneğin, dakikanın kesirli kısmı iki ondalık basamağa kadar verildiğinde, format ddd/1,mmmm/100,0/1 olur. |
| GPSDestBearingRef | `23` | Hedef noktaya yön verme için kullanılan referansı gösterir. 'T' gerçek yönü, 'M' ise manyetik yönü belirtir. |
| GPSDestBearing | `24` | Hedef noktaya yönü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır. |
| GPSDestDistanceRef | `25` | Hedef noktaya olan mesafeyi ifade etmek için kullanılan birimi gösterir. 'K', 'M' ve 'N' sırasıyla kilometre, mil ve knot anlamına gelir. |
| GPSDestDistance | `26` | Hedef noktaya olan mesafeyi gösterir. |
| GPSProcessingMethod | `27` | Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizisi. İlk bayt kullanılan karakter kodunu gösterir ve ardından yöntemin adı gelir. |
| GPSAreaInformation | `28` | GPS bölgesinin adını kaydeden bir karakter dizisi. İlk bayt kullanılan karakter kodunu gösterir ve ardından GPS bölgesinin adı gelir. |
| GPSDateStamp | `29` | UTC (Eşgüdümlü Evrensel Zaman) ile ilgili tarih ve saat bilgilerini kaydeden bir karakter dizisi. Format YYYY:MM:DD'dir. |
| GPSDifferential | `30` | GPS alıcısına diferansiyel düzeltmenin uygulanıp uygulanmadığını gösterir. |
| StripOffsets | `273` | Her şerit için, o şeridin bayt ofseti. Şerit bayt sayısının 64 Kbyte'ı aşmaması için bunun seçilmesi önerilir. Aux etiketi. |
| JPEGInterchangeFormat | `513` | JPEG sıkıştırmalı küçük resim verisinin başlangıç baytına (SOI) olan ofset. Bu, birincil görüntü JPEG verisi için kullanılmaz. |
| JPEGInterchangeFormatLength | `514` | JPEG sıkıştırmalı küçük resim verisinin bayt sayısı. Bu, birincil görüntü JPEG verisi için kullanılmaz. JPEG küçük resimler bölünmez, SOI'den EOI'ye kadar sürekli bir JPEG bit akışı olarak kaydedilir. Appn ve COM işaretçileri kaydedilmemelidir. Sıkıştırılmış küçük resimler, APP1'de kaydedilecek diğer tüm veriler dahil olmak üzere 64 Kbyte'ı geçmemelidir. |
| ExifIfdPointer | `34665` | Exif IFD'ye bir işaretçi. Interoperability, Exif IFD, TIFF'te belirtilen IFD ile aynı yapıya sahiptir. Ancak genellikle TIFF'teki gibi görüntü verisi içermez. |
| GPSIfdPointer | `34853` | gps ifd işaretçisi. |
| RowsPerStrip | `278` | Şerit başına satır sayısı. Görüntü şeritlere bölündüğünde bir şeritteki satır sayısını ifade eder. |
| StripByteCounts | `279` | Her şeritteki toplam bayt sayısı. |
| PixelXDimension | `40962` | Sıkıştırılmış veriye özgü bilgi. Bir sıkıştırılmış dosya kaydedildiğinde, dolgu verisi veya yeniden başlatma işareti olup olmamasına bakılmaksızın anlamlı görüntünün geçerli genişliği bu etikette kaydedilir. |
| PixelYDimension | `40963` | Sıkıştırılmış veriye özgü bilgi. Bir sıkıştırılmış dosya kaydedildiğinde, anlamlı görüntünün geçerli yüksekliği bu etikette kaydedilir. |
| Gamma | `42240` | Gamma değeri |
| SensitivityType | `34864` | Fotografik duyarlılık türü |
| StandardOutputSensitivity | `34865` | Kameranın standart çıkış duyarlılığını gösterir |
| RecommendedExposureIndex | `34866` | Önerilen pozlama indeksini gösterir |
| ISOSpeed | `34867` | ISO 12232'de tanımlanan iso hız değeri hakkında bilgi |
| ISOSpeedLatitudeYYY | `34868` | Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi yyy değerini gösterir |
| ISOSpeedLatitudeZZZ | `34869` | Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi zzz değerini gösterir |
| CameraOwnerName | `42032` | Kamera sahibinin adını içerir |
| BodySerialNumber | `42033` | Kamera gövdesi seri numarasını içerir |
| LensMake | `42035` | Bu etiket lens üreticisini kaydeder |
| LensModel | `42036` | Bu etiket lens`s model adını ve model numarasını kaydeder |
| LensSerialNumber | `42037` | Bu etiket değiştirilebilir lensin seri numarasını kaydeder |
| LensSpecification | `42034` | Bu etiket minimum odak uzaklığını, maksimum odak uzaklığını, minimum odak uzaklığındaki minimum F sayısını ve maksimum odak uzaklığındaki minimum F sayısını not eder |

### Ayrıca Bakınız

* namespace [Aspose.PSD.Exif](../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../)


