---
title: Enum ExifProperties
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Exif.ExifProperties Sıralama. Exif etiketleri listesi
type: docs
weight: 1000
url: /tr/net/aspose.psd.exif/exifproperties/
---
## ExifProperties enumeration

Exif etiketleri listesi

```csharp
public enum ExifProperties : ushort
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| ImageWidth | `256` | Satır başına piksel sayısına eşit olan görüntü verisi sütunlarının sayısı. |
| ImageLength | `257` | Görüntü verilerinin satır sayısı. |
| BitsPerSample | `258` | Görüntü bileşeni başına bit sayısı. Bu standartta, görüntünün her bileşeni 8 bittir, dolayısıyla bu etiketin değeri 8. 'dir. |
| Compression | `259` | Görüntü verileri için kullanılan sıkıştırma şeması. Birincil görüntü JPEG sıkıştırıldığında, bu atama gerekli değildir ve atlanmıştır. |
| PhotometricInterpretation | `262` | Piksel bileşimi. |
| ImageDescription | `270` | Görüntünün başlığını veren bir karakter dizisi. "1988 şirket pikniği" veya benzeri bir yorum olabilir. |
| Make | `271` | Kayıt ekipmanının üreticisi. Bu, görüntüyü oluşturan DSC, tarayıcı, video sayısallaştırıcı veya diğer ekipmanın üreticisidir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| Model | `272` | Ekipmanın model adı veya model numarası. Bu, görüntüyü oluşturan DSC, tarayıcı, video sayısallaştırıcı veya diğer ekipmanın model adı veya numarasıdır. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| Orientation | `274` | Satır ve sütunlar açısından görüntülenen resim yönü. |
| SamplesPerPixel | `277` | Piksel başına bileşen sayısı. Bu standart RGB ve YCbCr görüntüleri için geçerli olduğundan, bu etiket için ayarlanan değer 3. şeklindedir. |
| XResolution | `282` | ImageWidth yönünde ÇözünürlükBirimi başına piksel sayısı. Görüntü çözünürlüğü bilinmediğinde, 72 [dpi] belirlenir. |
| YResolution | `283` | ImageLength yönündeki ResolutionUnit başına piksel sayısı. XResolution ile aynı değer belirlenir. |
| PlanarConfiguration | `284` | Piksel bileşenlerinin parçalı mı yoksa düzlemsel biçimde mi kaydedildiğini gösterir. Bu alan mevcut değilse, TIFF varsayılanı olan 1 (yığın) varsayılır. |
| ResolutionUnit | `296` | XResolution ve YResolution ölçüm birimi. Aynı birim hem XResolution hem de YResolution için kullanılır. Görüntü çözünürlüğü bilinmiyorsa 2 (inç) belirlenir. |
| TransferFunction | `301` | Resim için tablo biçiminde açıklanan bir aktarım işlevi. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisinde ColorSpace tag. belirtilmiştir. |
| Software | `305` | Bu etiket, görüntüyü oluşturmak için kullanılan kameranın veya görüntü giriş cihazının yazılımının veya sabit yazılımının adını ve sürümünü kaydeder. Ayrıntılı format belirtilmemiştir, ancak aşağıda gösterilen örneğin izlenmesi önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| DateTime | `306` | Görüntü oluşturma tarihi ve saati. Exif standardında dosyanın değiştirildiği tarih ve saattir. |
| Artist | `315` | Bu etiket, kamera sahibinin, fotoğrafçının veya görüntü oluşturucunun adını kaydeder. Ayrıntılı format belirtilmemiştir, ancak birlikte çalışabilirliğin kolaylığı için bilgilerin aşağıdaki örnekteki gibi yazılması önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. Örn.) "Kamera sahibi, John Smith; Fotoğrafçı, Michael Brown; Görüntü yaratıcısı, Ken James" |
| WhitePoint | `318` | Görüntünün beyaz noktasının renkliliği. Normalde bu etiket gerekli değildir, çünkü renk alanı renk alanı bilgisinde belirtildiği için ColorSpace tag. |
| PrimaryChromaticities | `319` | Görüntünün üç ana renginin renkliliği. Renk alanı, renk alanı bilgisinde belirtildiği için normalde bu etiket gerekli değildir ColorSpace tag. |
| YCbCrCoefficients | `529` | RGB'den YCbCr görüntü verilerine dönüşüm için matris katsayıları. |
| YCbCrSubSampling | `530` | Renk bileşenlerinin parlaklık bileşenine göre örnekleme oranı. |
| YCbCrPositioning | `531` | Renk bileşenlerinin, parlaklık bileşenine göre konumu. Bu alan yalnızca JPEG sıkıştırılmış verileri veya sıkıştırılmamış YCbCr verileri için atanmıştır. TIFF varsayılan değeri 1'dir (ortalanmış); ancak Y:Cb:Cr = 4:2:2 olduğunda, TV sistemlerinde görüntülendiğinde görüntü kalitesini iyileştirmek için bu standartta 2 (birlikte yerleştirilmiş) veri kaydı için kullanılması önerilir. Bu alan mevcut olmadığında, okuyucu TIFF varsayılanını alır . Y:Cb:Cr = 4:2:0 durumunda, TIFF varsayılanı (ortalanmış) önerilir. Reader , her iki tür YCbCrPositioning'i destekleme yeteneğine sahip değilse, bu alandaki değerin değerinden bağımsız olarak TIFF varsayılanını izleyecektir. " okuyucularının hem merkezlenmiş hem de ortak konumlu konumlandırmayı destekleyebilmesi tercih edilir. |
| ReferenceBlackWhite | `532` | Referans siyah nokta değeri ve referans beyaz nokta değeri. TIFF'de hiçbir varsayılan verilmemiştir, ancak aşağıdaki değerler burada varsayılan olarak verilmiştir. Renk alanı, bir renk alanı bilgi etiketinde olarak belirtilir, default en uygun görüntü özelliklerini veren değerdir Birlikte çalışabilirlik bu koşullar |
| Copyright | `33432` | Telif hakkı bilgisi. Bu standartta etiket, hem fotoğrafçının hem de editörün telif haklarını belirtmek için kullanılır. Görüntü üzerinde hak iddia eden kişi veya kuruluşun telif hakkı bildirimidir. Bu alanına tarih ve hakları içeren Birlikte Çalışabilirlik copyright bildirimi yazılmalıdır; örneğin, "Telif hakkı, John Smith, 19xx. Tüm hakları saklıdır.". Bu standartta alan, her biri beyanın ayrı bir bölümüne kaydedilmiş olarak, hem fotoğrafçısının hem de editörün telif haklarını kaydeder. Fotoğrafçı ve editör telif hakları arasında açık bir ayrımı olduğunda, bunlar fotoğrafçının sırasına göre yazılacak ve ardından editör telif hakkı gelecek, NULL ile ayrılacak (bu durumda ifade ayrıca bir NULL ile bittiği için, iki NULL kodu vardır. ). Yalnızca fotoğrafçı telif hakkı verildiğinde, bir NULL kodu ile sonlandırılır. Yalnızca editör telif hakkı verildiğinde, fotoğrafçı telif hakkı part bir boşluktan oluşur ve onu sonlandıran bir NULL kodu içerir, ardından editör telif hakkı verilir. Alan boş bırakıldığında, is bilinmeyen olarak kabul edilir. |
| ExposureTime | `33434` | Maruz kalma süresi, saniye olarak verilir. |
| FNumber | `33437` | F numarası. |
| ExposureProgram | `34850` | Fotoğraf çekildiğinde pozlamayı ayarlamak için kamera tarafından kullanılan programın sınıfı. |
| SpectralSensitivity | `34852` | Kullanılan kameranın her bir kanalının spektral hassasiyetini gösterir. |
| PhotographicSensitivity | `34855` | ISO 12232. 'de belirtildiği gibi kameranın veya giriş cihazının ISO Hızını ve ISO Enlemini belirtir. |
| OECF | `34856` | ISO 14524. 'de belirtilen Opto-Elektrik Dönüştürme İşlevini (OECF) belirtir |
| ExifVersion | `36864` | Eski sürüm. |
| DateTimeOriginal | `36867` | Orijinal görüntü verilerinin oluşturulduğu tarih ve saat. |
| DateTimeDigitized | `36868` | Tarih saat sayısallaştırıldı. |
| ComponentsConfiguration | `37121` | Bileşen yapılandırması. |
| CompressedBitsPerPixel | `37122` | Sıkıştırılmış verilere özel; piksel başına sıkıştırılmış bitleri belirtir. |
| ShutterSpeedValue | `37377` | Deklanşör hızı değeri. |
| ApertureValue | `37378` | Mercek açıklık değeri. |
| BrightnessValue | `37379` | Parlaklık değeri. |
| ExposureBiasValue | `37380` | Pozlama önyargı değeri. |
| MaxApertureValue | `37381` | Maksimum diyafram değeri. |
| SubjectDistance | `37382` | Özneye metre olarak verilen mesafe. |
| MeteringMode | `37383` | Ölçüm modu. |
| LightSource | `37384` | Nazik ışık kaynağı. |
| Flash | `37385` | Görüntü çekildiğinde flaşın durumunu gösterir. |
| FocalLength | `37386` | Merceğin gerçek odak uzaklığı, mm. |
| SubjectArea | `37396` | Bu etiket, genel sahnede ana konunun konumunu ve alanını belirtir. |
| MakerNote | `37500` | Exif yazıcı üreticilerinin istenen bilgileri kaydetmesi için bir etiket. İçeriği üreticiye bağlıdır, ancak bu etiket kullanım amacı dışında kullanılmamalıdır. |
| UserComment | `37510` | Exif kullanıcılarının, ImageDescription etiketinin karakter kodu sınırlamaları olmadan, ImageDescription'dakilerin yanı sıra görüntüye anahtar kelimeler veya yorumlar yazabilmeleri için bir etiket. |
| SubsecTime | `37520` | DateTime etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| SubsecTimeOriginal | `37521` | DateTimeOriginal etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| SubsecTimeDigitized | `37522` | DateTimeDigitized etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| FlashpixVersion | `40960` | Bir FPXR dosyası tarafından desteklenen Flashpix biçimi sürümü. |
| ColorSpace | `40961` | Renk alanı bilgi etiketi (ColorSpace) her zaman renk alanı belirleyicisi olarak kaydedilir. |
| RelatedSoundFile | `40964` | İlgili ses dosyası. |
| FlashEnergy | `41483` | Işın Mum Gücü Saniyesi (BCPS) cinsinden ölçüldüğü şekliyle görüntünün çekildiği andaki flaş enerjisini gösterir. |
| SpatialFrequencyResponse | `41484` | Bu etiket, ISO 12233. 'de belirtildiği gibi, kamera veya giriş cihazı uzamsal frekans tablosunu ve SFR değerlerini görüntü genişliği, görüntü yüksekliği ve köşegen yönü yönünde kaydeder. |
| FocalPlaneXResolution | `41486` | Kamera odak düzlemindeki Odak Düzlemi Çözünürlük Birimi başına görüntü genişliği (X) yönündeki piksel sayısını belirtir. |
| FocalPlaneYResolution | `41487` | Kamera odak düzlemindeki Odak Düzlemi Çözünürlük Birimi başına görüntü yüksekliği (Y) yönündeki piksel sayısını gösterir. |
| FocalPlaneResolutionUnit | `41488` | FocalPlaneXResolution ve FocalPlaneYResolution ölçüm birimini belirtir. Bu değer, ResolutionUnit. ile aynıdır. |
| SubjectLocation | `41492` | Sahnedeki ana öznenin konumunu belirtir. Bu etiketin değeri, Rotation etiketine göre döndürme işleminden önce sol kenara göre ana konunun merkezindeki pikseli temsil eder. |
| ExposureIndex | `41493` | Görüntünün çekildiği sırada kamerada veya giriş cihazında seçilen poz indeksini gösterir. |
| SensingMethod | `41495` | Kamera veya giriş aygıtı üzerindeki görüntü sensörü tipini belirtir. |
| FileSource | `41728` | Dosya kaynağı. |
| SceneType | `41729` | Sahne tipini belirtir. Görüntüyü bir DSC kaydettiyse, bu etiket değeri her zaman 1'e ayarlanarak görüntünün doğrudan fotoğraflandığını gösterir. |
| CFAPattern | `41730` | Tek çipli bir renk alanı sensörü kullanıldığında, görüntü sensörünün renk filtresi dizisi (CFA) geometrik modelini belirtir. Tüm algılama yöntemleri için geçerli değildir. |
| CustomRendered | `41985` | Bu etiket, görüntü verileri üzerinde, çıktıya yönelik işleme gibi özel işlemlerin kullanıldığını gösterir. Özel işlem yapıldığında, okuyucunun daha fazla işlemeyi devre dışı bırakması veya en aza indirmesi beklenir. |
| ExposureMode | `41986` | Bu etiket, resim çekildiğinde ayarlanan pozlama modunu gösterir. Otomatik basamaklama modunda, kamera farklı pozlama ayarlarında aynı sahnenin bir dizi karesini çeker. |
| WhiteBalance | `41987` | Bu etiket, resim çekildiğinde ayarlanan beyaz dengesi modunu gösterir. |
| DigitalZoomRatio | `41988` | Bu etiket, resim çekildiğinde dijital yakınlaştırma oranını gösterir. Kaydedilen değerin payı 0 ise bu, dijital yakınlaştırmanın kullanılmadığını gösterir. |
| FocalLengthIn35MmFilm | `41989` | Bu etiket, 35 mm'lik bir film kamerası varsayıldığında mm cinsinden eşdeğer odak uzaklığını gösterir. 0 değeri, odak uzunluğunun bilinmediği anlamına gelir. Bu etiketin FocalLength etiketinden farklı olduğunu unutmayın. |
| SceneCaptureType | `41990` | Bu etiket, çekilen sahnenin türünü belirtir. Görüntünün çekildiği modu kaydetmek için de kullanılabilir. |
| GainControl | `41991` | Bu etiket, genel görüntü kazanç ayarının derecesini gösterir. |
| Contrast | `41992` | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan kontrast işleme yönünü gösterir. |
| Saturation | `41993` | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan doygunluk işleme yönünü gösterir. |
| Sharpness | `41994` | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan keskinlik işleme yönünü belirtir |
| DeviceSettingDescription | `41995` | Bu etiket, belirli bir kamera modelinin fotoğraf çekme koşulları hakkında bilgi verir. Etiket, yalnızca okuyucudaki fotoğraf çekme koşullarını belirtmek için kullanılır. |
| SubjectDistanceRange | `41996` | Bu etiket, özneye olan mesafeyi gösterir. |
| ImageUniqueID | `42016` | Resmin benzersiz kimliği. |
| GPSVersionID | `0` | GPSInfoIFD. sürümünü gösterir |
| GPSLatitudeRef | `1` | Enlemin kuzey mi güney mi olduğunu gösterir. |
| GPSLatitude | `2` | Enlemi gösterir. Enlem, sırasıyla derece, dakika ve saniyeyi veren üç RATIONAL değeri olarak ifade edilir. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik biçim dd/1,mm/1,ss/1 olacaktır. Dereceler ve dakikalar kullanıldığında ve örneğin dakikanın kesirleri iki ondalık basamağa kadar verildiğinde, biçim dd/1,mmmm/100,0/1. olacaktır. |
| GPSLongitudeRef | `3` | Boylamın doğu mu yoksa batı boylamı mı olduğunu gösterir. |
| GPSLongitude | `4` | Boylamı gösterir. Boylam, sırasıyla derece, dakika ve saniyeyi veren üç RATIONAL değeri olarak ifade edilir. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik biçim dd/1,mm/1,ss/1 olacaktır. Dereceler ve dakikalar kullanıldığında ve örneğin dakikanın kesirleri iki ondalık basamağa kadar verildiğinde, biçim ddd/1,mmmm/100,0/1. olacaktır. |
| GPSAltitudeRef | `5` | Referans yükseklik olarak kullanılan yüksekliği gösterir. Referans deniz seviyesi ise ve rakım deniz seviyesinden yüksekse, 0 verilir. Rakım deniz seviyesinin altındaysa 1 değeri verilir ve GPSAltitude etiketinde içinde yükseklik mutlak değer olarak belirtilir. |
| GPSAltitude | `6` | GPSAltitudeRef'teki referansa göre yüksekliği gösterir. Rakım bir RATIONAL değeri olarak ifade edilir. Referans birimi metredir. |
| GPSTimestamp | `7` | Saati UTC (Eşgüdümlü Evrensel Saat) olarak gösterir. Zaman Damgası, saat, dakika ve saniyeyi veren üç RATIONAL değeri olarak ifade edilir. |
| GPSSatellites | `8` | Ölçümler için kullanılan GPS uydularını gösterir. Bu etiket, uydu sayısını, kimlik numarasını, yükseklik açısını, azimutu, SNR'yi ve ASCII notasyonundaki diğer bilgileri tanımlamak için kullanılabilir. Biçim not belirtilmedi. GPS alıcısı ölçüm yapamıyorsa, etiketin değeri NULL. olarak ayarlanmalıdır. |
| GPSStatus | `9` | Görüntü kaydedildiğinde GPS alıcısının durumunu gösterir. |
| GPSMeasureMode | `10` | GPS ölçüm modunu gösterir. - 2- veya 3- boyutlu. |
| GPSDOP | `11` | GPS DOP'u (veri hassasiyet derecesi) gösterir. İki boyutlu ölçüm sırasında bir HDOP değeri yazılır, ve üç boyutlu ölçüm sırasında PDOP. |
| GPSSpeedRef | `12` | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi belirtir. 'K' 'M' ve 'N', kilometre/ saat, mil/saat ve deniz milini temsil eder. |
| GPSSpeed | `13` | GPS alıcısının hareket hızını gösterir. |
| GPSTrackRef | `14` | GPS alıcı hareketinin yönünü vermek için referansı gösterir. 'T' gerçek yönü ve 'M' manyetik yönü ifade eder. |
| GPSTrack | `15` | GPS alıcısının hareket yönünü gösterir. Değer aralığı 0,00 ile 359,99. arasındadır. |
| GPSImgDirectionRef | `16` | Yakalandığında görüntünün yönünü vermek için referansı belirtir. 'T' gerçek yönü ve 'M' manyetik yönü ifade eder. |
| GPSImgDirection | `17` | Görüntünün yakalandığı andaki yönünü belirtir. Değer aralığı 0,00 ile 359,99. arasındadır. |
| GPSMapDatum | `18` | GPS alıcısı tarafından kullanılan jeodezik araştırma verilerini gösterir. |
| GPSDestLatitudeRef | `19` | Varış noktasının enleminin kuzey mi güney mi olduğunu gösterir. ASCII değeri 'N' kuzey enlemini ve 'S' güney enlemini gösterir. |
| GPSDestLatitude | `20` | Varış noktasının enlemini gösterir. Enlem, sırasıyla derecesini, dakikasını ve saniyesini veren üç RATIONAL değeri olarak ifade edilir. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik bir formatı dd/1,mm/1,ss/1 olacaktır. Dereceler ve dakikalar kullanıldığında ve örneğin dakika kesirleri iki ondalık basamağa kadar verildiğinde , biçim dd/1,mmmm/100,0/1. olacaktır. |
| GPSDestLongitudeRef | `21` | Varış noktasının boylamının doğu mu yoksa batı boylamı mı olduğunu gösterir. ASCII 'E' doğu boylamını, ve 'W' batı boylamını gösterir. |
| GPSDestLongitude | `22` | Hedef noktanın boylamını gösterir. Boylam, sırasıyla derecesini, dakikasını ve saniyesini veren üç RATIONAL değeri olarak ifade edilir. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik bir biçimi ddd/1,mm/1,ss/1 olur. Dereceler ve dakikalar kullanıldığında ve örneğin dakika kesirleri iki ondalık basamağa kadar verildiğinde , biçim ddd/1,mmmm/100,0/1. olacaktır. |
| GPSDestBearingRef | `23` | Yönü varış noktasına vermek için kullanılan referansı gösterir. 'T' gerçek yönü ve 'M' manyetik yönü ifade eder. |
| GPSDestBearing | `24` | Varış noktasına olan yönü gösterir. Değer aralığı 0,00 ile 359,99. arasındadır. |
| GPSDestDistanceRef | `25` | Varış noktasına olan mesafeyi ifade etmek için kullanılan birimi belirtir. 'K', 'M' ve 'N' kilometreleri, mil ve düğümleri temsil eder. |
| GPSDestDistance | `26` | Hedef noktaya olan mesafeyi gösterir. |
| GPSProcessingMethod | `27` | Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizisi. İlk bayt, kullanılan karakter kodunu gösterir ve bunu yöntemin adı takip eder. |
| GPSAreaInformation | `28` | GPS alanının adını kaydeden bir karakter dizisi. İlk bayt, kullanılan karakter kodunu gösterir ve bunu GPS alanının adı izler. |
| GPSDateStamp | `29` | UTC 'ye (Koordineli Evrensel Zaman) göre tarih ve saat bilgilerini kaydeden bir karakter dizisi. Biçim YYYY:AA:GG. şeklindedir. |
| GPSDifferential | `30` | GPS alıcısına diferansiyel düzeltmenin uygulanıp uygulanmadığını gösterir. |
| StripOffsets | `273` | Her şerit için, o şeridin bayt ofseti. Şerit bayt sayısı 64 Kbyte'ı geçmeyecek şekilde bunun seçilmesi önerilir. Aux tag. |
| JPEGInterchangeFormat | `513` | JPEG sıkıştırılmış küçük resim verilerinin başlangıç baytına (SOI) uzaklık. Bu, birincil görüntü JPEG verileri için kullanılmaz. |
| JPEGInterchangeFormatLength | `514` | JPEG sıkıştırılmış küçük resim verilerinin bayt sayısı. Bu, birincil görüntü JPEG verileri için kullanılmaz. JPEG küçük resimleri bölünmez, ancak SOI'den EOI'ye sürekli bir JPEG bit akışı olarak kaydedilir. Appn ve COM işaretleri kaydedilmemelidir. Sıkıştırılmış küçük resimler, APP1. 'de kaydedilecek diğer tüm veriler dahil olmak üzere en fazla 64 Kbyte olarak kaydedilmelidir. |
| ExifIfdPointer | `34665` | Exif IFD'ye bir işaretçi. Birlikte çalışabilirlik, Exif IFD, TIFF'de belirtilen IFD ile aynı yapıya sahiptir. ancak normalde TIFF. durumunda olduğu gibi görüntü verilerini içermez. |
| GPSIfdPointer | `34853` | gps ifd işaretçisi. |
| RowsPerStrip | `278` | Şerit başına satır sayısı. Bu, bir görüntü şeritlere bölündüğünde, bir şeridin görüntüsündeki satır sayısıdır. |
| StripByteCounts | `279` | Her şeritteki toplam bayt sayısı. |
| PixelXDimension | `40962` | Sıkıştırılmış verilere özel bilgiler. Sıkıştırılmış bir dosya kaydedildiğinde, dolgu verisi veya yeniden başlatma işaretçisi olsun ya da olmasın, anlamlı görüntünün geçerli genişliği bu etikete kaydedilmelidir. |
| PixelYDimension | `40963` | Sıkıştırılmış verilere özel bilgiler. Sıkıştırılmış bir dosya kaydedildiğinde, anlamlı görüntünün geçerli yüksekliği bu etikete kaydedilmelidir |
| Gamma | `42240` | Gama değeri |
| SensitivityType | `34864` | Fotoğraf hassasiyeti türü |
| StandardOutputSensitivity | `34865` | camera 'nin standart çıkış hassasiyetini gösterir |
| RecommendedExposureIndex | `34866` | Önerilen maruz kalma indeksini gösterir |
| ISOSpeed | `34867` | ISO 12232 'de tanımlanan iso hız değeri hakkında bilgi |
| ISOSpeedLatitudeYYY | `34868` | Bu etiket, ISO 12232 'de tanımlanan ISO hız enlemi yyy değerini gösterir. |
| ISOSpeedLatitudeZZZ | `34869` | Bu etiket, ISO 12232 'de tanımlanan ISO hız enlemi zzz değerini gösterir. |
| CameraOwnerName | `42032` | Kamera sahibi adını içerir |
| BodySerialNumber | `42033` | Kamera gövdesi seri numarasını içerir |
| LensMake | `42035` | Bu etiket lens üreticisini kaydeder |
| LensModel | `42036` | Bu etiket, merceğin model adını ve model numarasını kaydeder |
| LensSerialNumber | `42037` | Bu etiket, değiştirilebilir lensin seri numarasını kaydeder |
| LensSpecification | `42034` | Bu etiket minimum odak uzaklığını, maksimum odak uzaklığını, minimum odak uzaklığında minimum F sayısını ve maksimum odak uzaklığında minimum F sayısını not eder |

### Ayrıca bakınız

* ad alanı [Aspose.PSD.Exif](../../aspose.psd.exif/)
* toplantı [Aspose.PSD](../../)


