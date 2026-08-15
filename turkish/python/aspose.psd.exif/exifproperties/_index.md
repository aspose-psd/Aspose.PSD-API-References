---
title: "ExifProperties Enumerasyonu"
type: docs
weight: 160
url: /tr/python-net/aspose.psd.exif/exifproperties/
---

Exif etiketleri listesi

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifProperties

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| APERTURE_VALUE | Lens diyafram değeri. |
| ARTIST | Bu etiket, kamera sahibi, fotoğrafçı veya görüntü oluşturucusunun adını kaydeder. Ayrıntılı format belirtilmemiştir, ancak bilgi, birlikte çalışabilirliği kolaylaştırmak için aşağıdaki örnekteki gibi yazılması önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | Görüntü bileşeni başına bit sayısı. Bu standartta görüntünün her bileşeni 8 bitten oluşur, bu nedenle bu etiketin değeri 8'dir. |
| BODY_SERIAL_NUMBER | Kamera gövdesi seri numarasını içerir. |
| BRIGHTNESS_VALUE | Parlaklık değeri. |
| CAMERA_OWNER_NAME | Kamera sahibi adını içerir. |
| CFA_PATTERN | Tek çipli renk alan sensörü kullanıldığında görüntü sensörünün renk filtresi dizisi (CFA) geometrik desenini gösterir. Tüm algılama yöntemlerine uygulanmaz. |
| COLOR_SPACE | Renk uzayı bilgi etiketi (ColorSpace) her zaman renk uzayı belirteci olarak kaydedilir. |
| COMPONENTS_CONFIGURATION | Bileşen yapılandırması. |
| COMPRESSED_BITS_PER_PIXEL | Sıkıştırılmış veriye özgüdür; piksel başına sıkıştırılmış bit sayısını belirtir. |
| COMPRESSION | Görüntü verileri için kullanılan sıkıştırma şeması. Birincil görüntü JPEG ile sıkıştırıldığında, bu tanımlama gerekli değildir ve atlanır. |
| CONTRAST | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan kontrast işleme yönünü gösterir. |
| COPYRIGHT | Telif hakkı bilgisi. Bu standartta etiket, fotoğrafçı ve editör telif haklarını<br/>                göstermek için kullanılır. Bu, görüntünün haklarını talep eden kişi veya kuruluşun<br/>                telif hakkı bildirimidir. Bu alana, tarih ve hakları içeren Interoperability telif hakkı<br/>                beyanı yazılmalıdır; örn., "Copyright, John Smith, 19xx. All rights<br/>                reserved.". Bu standartta alan, fotoğrafçı ve editör telif haklarını<br/>                kaydeder; her biri beyanın ayrı bir bölümünde yer alır. Fotoğrafçı ve editör telif hakları arasında net bir ayrım olduğunda, bunlar<br/>                fotoğrafçıdan sonra editör telif hakkı şeklinde, NULL ile ayrılarak<br/>                yazılır (bu durumda beyan NULL ile bittiği için iki NULL kodu bulunur). Yalnızca fotoğrafçı telif hakkı verildiğinde, bir NULL kodu ile sonlandırılır. Yalnızca<br/>                editör telif hakkı verildiğinde, fotoğrafçı telif hakkı bölümü<br/>                bir boşluk ve ardından bir sonlandırıcı NULL kodundan oluşur, ardından<br/>                editör telif hakkı verilir. Alan boş bırakıldığında, <br/>                bilinmeyen olarak kabul edilir. |
| CUSTOM_RENDERED | Bu etiket, görüntü verileri üzerinde çıktı odaklı işleme gibi özel işleme kullanımını gösterir. Özel işleme gerçekleştirildiğinde, okuyucunun daha fazla işleme devre dışı bırakması veya en aza indirmesi beklenir. |
| DATE_TIME | Görüntünün oluşturulma tarihi ve saati. Exif standardında, dosyanın değiştirildiği tarih ve saat olarak tanımlanır. |
| DATE_TIME_DIGITIZED | Dijitalleştirme tarihi ve saati. |
| DATE_TIME_ORIGINAL | Orijinal görüntü verisinin oluşturulduğu tarih ve saat. |
| DEVICE_SETTING_DESCRIPTION | Bu etiket, belirli bir kamera modelinin fotoğraf çekim koşulları hakkında bilgi verir. Etiket yalnızca okuyucuda fotoğraf çekim koşullarını göstermek için kullanılır. |
| DIGITAL_ZOOM_RATIO | Bu etiket, görüntü çekildiğinde dijital zoom oranını gösterir. Kaydedilen değerin payı 0 ise, dijital zoomun kullanılmadığını gösterir. |
| EXIF_IFD_POINTER | Exif IFD'ye bir işaretçi. Interoperability, Exif IFD, TIFF'te belirtilen IFD ile aynı yapıya sahiptir. Ancak genellikle, TIFF'teki gibi görüntü verisi içermez. |
| EXIF_VERSION | Exif sürümü. |
| EXPOSURE_BIAS_VALUE | Pozlama sapma değeri. |
| EXPOSURE_INDEX | Görüntü yakalandığında kamera veya giriş cihazı tarafından seçilen pozlama indeksini gösterir. |
| EXPOSURE_MODE | Bu etiket, görüntü çekildiğinde ayarlanan pozlama modunu gösterir. Otomatik bracketing modunda, kamera aynı sahnenin farklı pozlama ayarlarıyla bir dizi kare çeker. |
| EXPOSURE_PROGRAM | Fotoğraf çekildiğinde kameranın pozlamayı ayarlamak için kullandığı program sınıfı. |
| EXPOSURE_TIME | Pozlama süresi, saniye cinsinden verilir. |
| FILE_SOURCE | Dosya kaynağı. |
| Flaş | Görüntü çekildiğinde flaşın durumunu gösterir. |
| FLASHPIX_VERSION | Bir FPXR dosyası tarafından desteklenen Flashpix format sürümü. |
| FLASH_ENERGY | Görüntünün yakalandığı anda ölçülen ışık çubuğu enerji değerini Beam Candle Power Seconds (BCPS) cinsinden gösterir. |
| FOCAL_LENGTH | Lensin gerçek odak uzaklığı, mm cinsinden. |
| FOCAL_LENGTH_IN_35_MM_FILM | Bu etiket, 35mm film kamerası varsayımıyla eşdeğer odak uzaklığını mm cinsinden gösterir. 0 değeri odak uzaklığının bilinmediği anlamına gelir. Bu etiketin FocalLength etiketinden farklı olduğunu unutmayın. |
| FOCAL_PLANE_RESOLUTION_UNIT | FocalPlaneXResolution ve FocalPlaneYResolution ölçümü için kullanılan birimi gösterir. Bu değer ResolutionUnit ile aynıdır. |
| FOCAL_PLANE_X_RESOLUTION | Kamera odak düzleminde FocalPlaneResolutionUnit başına görüntü genişliği (X) yönündeki piksel sayısını gösterir. |
| FOCAL_PLANE_Y_RESOLUTION | Kamera odak düzleminde FocalPlaneResolutionUnit başına görüntü yüksekliği (Y) yönündeki piksel sayısını gösterir. |
| F_NUMBER | F numarası. |
| GAIN_CONTROL | Bu etiket, genel görüntü kazanç ayarının derecesini gösterir. |
| GAMMA | Gamma değeri |
| GPSDOP | GPS DOP (veri kesinlik derecesi) gösterir. İki boyutlu ölçüm sırasında bir HDOP değeri yazılır,<br/>                üç boyutlu ölçüm sırasında ise PDOP. |
| GPS_ALTITUDE | GPSAltitudeRef içindeki referansa dayalı yüksekliği gösterir. Yükseklik tek bir RATIONAL değer olarak ifade edilir.<br/>                Referans birimi metredir. |
| GPS_ALTITUDE_REF | Referans yüksekliği olarak kullanılan yüksekliği gösterir. Referans deniz seviyesiyse ve yükseklik deniz seviyesinin üzerindeyse,<br/>                0 verilir. Yükseklik deniz seviyesinin altındaysa, 1 değeri verilir ve yükseklik GPSAltitude etiketinde mutlak değer olarak gösterilir. |
| GPS_AREA_INFORMATION | GPS bölgesinin adını kaydeden bir karakter dizisidir. İlk bayt kullanılan karakter kodunu gösterir,<br/>                ardından GPS bölgesinin adı gelir. |
| GPS_DATE_STAMP | UTC'ye (Eşgüdümlü Evrensel Zaman) göre tarih ve saat bilgisini kaydeden bir karakter dizisidir<br/>                (Koordineli Evrensel Zaman). Format YYYY:MM:DD şeklindedir. |
| GPS_DEST_BEARING | Hedef noktaya doğru yönü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır. |
| GPS_DEST_BEARING_REF | Hedef noktaya yön vermek için kullanılan referansı gösterir. 'T' gerçek yönü, 'M' ise manyetik yönü belirtir<br/>                . |
| GPS_DEST_DISTANCE | Hedef noktaya olan mesafeyi gösterir. |
| GPS_DEST_DISTANCE_REF | Hedef noktaya olan mesafeyi ifade etmek için kullanılan birimi gösterir. 'K', 'M' ve 'N' sırasıyla kilometre, mil<br/>                ve knot anlamına gelir. |
| GPS_DEST_LATITUDE | Hedef noktanın enlemini gösterir. Enlem, sırasıyla derece, dakika ve saniyeyi veren üç RATIONAL değer olarak ifade edilir.<br/>                Enlem derece, dakika ve saniye olarak ifade edilirse, tipik bir format dd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin, dakikanın kesirleri iki ondalık basamağa kadar verildiğinde, format dd/1,mmmm/100,0/1 şeklinde olur. |
| GPS_DEST_LATITUDE_REF | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösterir. ASCII değeri 'N' kuzey enlemini, 'S' ise güney enlemini gösterir<br/>                . |
| GPS_DEST_LONGITUDE | Hedef noktanın boylamını gösterir. Boylam, sırasıyla derece, dakika ve saniyeyi veren üç RATIONAL değer olarak ifade edilir.<br/>                Boylam derece, dakika ve saniye olarak ifade edilirse, tipik bir format ddd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin, dakikanın kesirleri iki ondalık basamağa kadar verildiğinde, format ddd/1,mmmm/100,0/1 şeklinde olur. |
| GPS_DEST_LONGITUDE_REF | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösterir. ASCII 'E' doğu boylamını,<br/>                'W' ise batı boylamını gösterir. |
| GPS_DIFFERENTIAL | GPS alıcısına diferansiyel düzeltmenin uygulanıp uygulanmadığını gösterir. |
| GPS_IFD_POINTER | GPS IFD işaretçisi. |
| GPS_IMG_DIRECTION | Görüntünün çekildiği yönü gösterir. Değer aralığı 0,00 ile 359,99 arasındadır. |
| GPS_IMG_DIRECTION_REF | Görüntünün çekildiği yönün referansını gösterir. 'T' gerçek yönü, 'M' ise<br/>                manyetik yönü belirtir. |
| GPS_LATITUDE | Enlemi gösterir. Enlem, derece, dakika ve<br/>                saniyeleri veren üç RATIONAL değer olarak ifade edilir. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik format dd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin, dakikanın kesirleri iki<br/>                ondalık basamağa kadar verildiğinde, format dd/1,mmmm/100,0/1 şeklindedir. |
| GPS_LATITUDE_REF | Enlemin kuzey mi yoksa güney mi olduğunu gösterir. |
| GPS_LONGITUDE | Boylamı gösterir. Boylam, derece, dakika ve<br/>                saniyeleri veren üç RATIONAL değer olarak ifade edilir. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik format ddd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin, dakikanın kesirleri iki<br/>                ondalık basamağa kadar verildiğinde, format ddd/1,mmmm/100,0/1 şeklindedir. |
| GPS_LONGITUDE_REF | Boylamın doğu mu yoksa batı mı olduğunu gösterir. |
| GPS_MAP_DATUM | GPS alıcısı tarafından kullanılan jeodezik ölçüm verilerini gösterir. |
| GPS_MEASURE_MODE | GPS ölçüm modunu gösterir. - 2- veya 3- boyutlu. |
| GPS_PROCESSING_METHOD | Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizisi.<br/>                İlk bayt kullanılan karakter kodunu gösterir ve ardından yöntemin adı<br/>                gelir. |
| GPS_SATELLITES | Ölçümler için kullanılan GPS uydularını gösterir. Bu etiket, uydu sayısını,<br/>                uydu kimlik numarasını, yükselti açısını, azimutu, SNR ve diğer bilgileri ASCII notasyonunda tanımlamak için kullanılabilir. Biçim belirtilmemiştir. GPS alıcısı ölçüm yapamıyorsa, etiket değeri NULL olarak ayarlanmalıdır. |
| GPS_SPEED | GPS alıcı hareketinin hızını gösterir. |
| GPS_SPEED_REF | GPS alıcı hareket hızı birimini ifade etmek için kullanılan birimi gösterir. 'K' 'M' ve 'N' sırasıyla kilometre/saat,<br/>                mil/saat ve knot anlamına gelir. |
| GPS_STATUS | Görüntü kaydedildiğinde GPS alıcının durumunu gösterir. |
| GPS_TIMESTAMP | Zamanı UTC (Eşgüdümlü Evrensel Zaman) olarak gösterir. TimeStamp üç RATIONAL değerle saat, dakika ve saniyeyi verir.<br/>                 |
| GPS_TRACK | GPS alıcı hareket yönünü gösterir. Değer aralığı 0,00 ile 359,99 arasındadır. |
| GPS_TRACK_REF | GPS alıcı hareket yönü için referansı gösterir. 'T' gerçek yönü, 'M' ise<br/>                manyetik yönü belirtir. |
| GPS_VERSION_ID | GPSInfoIFD sürümünü gösterir. |
| IMAGE_DESCRIPTION | A karakter dizisi, görüntünün başlığını verir. "1988 şirket pikniği" gibi bir yorum olabilir. |
| IMAGE_LENGTH | Görüntü verisinin satır sayısı. |
| IMAGE_UNIQUE_ID | Görüntünün benzersiz kimliği. |
| IMAGE_WIDTH | Görüntü verisinin sütun sayısı, satır başına piksel sayısına eşittir. |
| ISO_SPEED | ISO 12232'de tanımlanan iso hız değeri hakkında bilgi. |
| ISO_SPEED_LATITUDE_YYY | Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi yyy değerini gösterir. |
| ISO_SPEED_LATITUDE_ZZZ | Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi zzz değerini gösterir. |
| JPEG_INTERCHANGE_FORMAT | JPEG sıkıştırmalı küçük resim verisinin başlangıç baytı (SOI) ofseti. Bu, birincil görüntü JPEG verisi için kullanılmaz. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | JPEG sıkıştırmalı küçük resim verisinin bayt sayısı. Bu, birincil görüntü JPEG verisi için kullanılmaz. JPEG küçük resimler bölünmez, SOI'den EOI'ye kadar kesintisiz bir JPEG bit akışı olarak kaydedilir. Appn ve COM işaretçileri kaydedilmemelidir. Sıkıştırılmış küçük resimler, APP1'de kaydedilecek diğer tüm veriler dahil olmak üzere, 64 Kbaytı aşmayacak şekilde kaydedilmelidir. |
| LENS_MAKE | Bu etiket lens üreticisini kaydeder. |
| LENS_MODEL | Bu etiket lensin model adını ve model numarasını kaydeder. |
| LENS_SERIAL_NUMBER | Bu etiket değiştirilebilir lensin seri numarasını kaydeder. |
| LENS_SPECIFICATION | Bu etiket minimum odak uzaklığını, maksimum odak uzaklığını, minimum odak uzaklığındaki minimum F sayısını ve maksimum odak uzaklığındaki minimum F sayısını belirtir. |
| LIGHT_SOURCE | Işık kaynağının türü. |
| MAKE | Kayıt ekipmanının üreticisi. Bu, görüntüyü oluşturan DSC, tarayıcı, video dijitalleştirici veya diğer ekipmanın üreticisidir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| MAKER_NOTE | Exif yazarlarının üreticileri için istenen herhangi bir bilgiyi kaydetmek amacıyla bir etiket. İçerik üreticinin takdirine bağlıdır, ancak bu etiket yalnızca amaçlandığı şekilde kullanılmalıdır. |
| MAX_APERTURE_VALUE | Maksimum diyafram değeri. |
| METERING_MODE | Ölçüm modu. |
| MODEL | Ekipmanın model adı veya model numarası. Bu, görüntüyü oluşturan DSC, tarayıcı, video dijitalleştirici veya diğer ekipmanın model adı veya numarasıdır. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| OECF | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) gösterir. |
| ORIENTATION | Satır ve sütun açısından görüntü yönelimi. |
| PHOTOGRAPHIC_SENSITIVITY | ISO 12232'de belirtilen kamera veya giriş cihazının ISO Hızı ve ISO Enlemini gösterir. |
| PHOTOMETRIC_INTERPRETATION | Piksel bileşimi. |
| PIXEL_X_DIMENSION | Sıkıştırılmış veriye özgü bilgiler. Bir sıkıştırılmış dosya kaydedildiğinde, anlamlı görüntünün geçerli genişliği, dolgu verisi veya yeniden başlatma işareti olup olmamasına bakılmaksızın bu etikette kaydedilmelidir. |
| PIXEL_Y_DIMENSION | Sıkıştırılmış veriye özgü bilgiler. Bir sıkıştırılmış dosya kaydedildiğinde, anlamlı görüntünün geçerli yüksekliği bu etikette kaydedilmelidir. |
| PLANAR_CONFIGURATION | Piksel bileşenlerinin chunky (parçalı) ya da planar (düzlemsel) formatta kaydedilip kaydedilmediğini gösterir. Bu alan yoksa, TIFF varsayılanı 1 (chunky) kabul edilir. |
| PRIMARY_CHROMATICITIES | Görüntünün üç ana renginin renk doygunluğu. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketinde belirtilir. |
| RECOMMENDED_EXPOSURE_INDEX | Önerilen pozlama indeksini gösterir |
| REFERENCE_BLACK_WHITE | Referans siyah nokta değeri ve referans beyaz nokta<br/>                değeri. TIFF'te varsayılanlar verilmez, ancak aşağıdaki değerler burada varsayılan olarak sunulmuştur.<br/>                Renk uzayı, bir renk uzayı bilgi etiketi içinde ilan edilir,<br/>                varsayılan olarak<br/>                optimal görüntü özelliklerini sağlayan değer olur<br/>                Bu koşullar altında birlikte çalışabilirlik |
| RELATED_SOUND_FILE | İlgili ses dosyası. |
| RESOLUTION_UNIT | XResolution ve YResolution ölçümü için kullanılan birim. Aynı birim hem XResolution hem de YResolution için kullanılır. Görüntü çözünürlüğü bilinmiyorsa, 2 (inç) olarak atanır. |
| ROWS_PER_STRIP | Şerit başına satır sayısı. Görüntü şeritlere bölündüğünde bir şeritteki satır sayısını ifade eder. |
| SAMPLES_PER_PIXEL | Piksel başına bileşen sayısı. Bu standart RGB ve YCbCr görüntülerine uygulandığından, bu etiket için ayarlanan değer 3'tür. |
| SATURATION | Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan doygunluk işleme yönünü gösterir. |
| SCENE_CAPTURE_TYPE | Bu etiket, çekilen sahnenin türünü gösterir. Ayrıca görüntünün çekildiği modu kaydetmek için de kullanılabilir. |
| SCENE_TYPE | Sahne türünü gösterir. Eğer bir DSC görüntüyü kaydettiyse, bu etiket değeri her zaman 1 olarak ayarlanmalı ve görüntünün doğrudan fotoğraf çekildiğini gösterir. |
| SENSING_METHOD | Kamera veya giriş cihazındaki görüntü sensörünün tipini gösterir. |
| SENSITIVITY_TYPE | Fotoğrafik duyarlılık türü |
| SHARPNESS | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan keskinlik işleme yönünü gösterir |
| SHUTTER_SPEED_VALUE | Enstantane hızı değeri. |
| SOFTWARE | Bu etiket, görüntüyü oluşturmak için kullanılan kamera veya görüntü giriş cihazının yazılım veya donanım (firmware) adını ve sürümünü kaydeder. Ayrıntılı format belirtilmemiştir, ancak aşağıda gösterilen örnek izlenmesi önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| SPATIAL_FREQUENCY_RESPONSE | Bu etiket, ISO 12233'te belirtildiği gibi, görüntü genişliği, görüntü yüksekliği ve diyagonal yönde kamera veya giriş cihazının uzaysal frekans tablosu ve SFR değerlerini kaydeder. |
| SPECTRAL_SENSITIVITY | Kullanılan kameranın her kanalının spektral duyarlılığını gösterir. |
| STANDARD_OUTPUT_SENSITIVITY | Kameranın standart çıkış duyarlılığını gösterir |
| STRIP_BYTE_COUNTS | Her şeritteki toplam bayt sayısı. |
| STRIP_OFFSETS | Her şerit için, o şeridin bayt ofseti. Şerit bayt sayısının 64 Kbaytı geçmemesi için bunun seçilmesi önerilir.<br/>                Aux etiket. |
| SUBJECT_AREA | Bu etiket, genel sahnedeki ana konunun konumunu ve alanını gösterir |
| SUBJECT_DISTANCE | Metre cinsinden konuya olan mesafe. |
| SUBJECT_DISTANCE_RANGE | Bu etiket, konuya olan mesafeyi gösterir |
| SUBJECT_LOCATION | Sahnedeki ana konunun konumunu gösterir. Bu etiketin değeri, Döndürme etiketiyle belirtilen döndürme işleminden önce, ana konunun merkezindeki pikseli sol kenara göre temsil eder. |
| SUBSEC_TIME | DateTime etiketi için saniyenin kesirlerini kaydetmekte kullanılan bir etiket. |
| SUBSEC_TIME_DIGITIZED | DateTimeDigitized etiketi için saniyenin kesirlerini kaydetmek için kullanılan bir etiket. |
| SUBSEC_TIME_ORIGINAL | DateTimeOriginal etiketi için saniyenin kesirlerini kaydetmek için kullanılan bir etiket. |
| TRANSFER_FUNCTION | Görüntü için tablo biçiminde tanımlanan bir aktarım fonksiyonu. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketiyle belirtilir. |
| USER_COMMENT | Exif kullanıcılarının ImageDescription içindeki anahtar kelimeler ve yorumların yanı sıra görüntüye anahtar kelimeler veya yorumlar yazabilmesi için bir etiket ve ImageDescription etiketinin karakter kodu sınırlamalarına tabi değildir. |
| WHITE_BALANCE | Bu etiket, görüntünün çekildiği sırada ayarlanan beyaz dengesi modunu gösterir. |
| WHITE_POINT | Görüntünün beyaz noktasının kromatikliği. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketiyle belirtilir. |
| X_RESOLUTION | ImageWidth yönündeki ResolutionUnit başına piksel sayısı. Görüntü çözünürlüğü bilinmediğinde 72 [dpi] olarak atanır. |
| Y_CB_CR_COEFFICIENTS | RGB'den YCbCr görüntü verisine dönüşüm için matris katsayıları. |
| Y_CB_CR_POSITIONING | Krominans bileşenlerinin parlaklık bileşenine göre konumu. Bu alan yalnızca<br/>                JPEG sıkıştırmalı veri veya sıkıştırılmamış YCbCr veri için belirlenir. TIFF<br/>                varsayılanı 1 (ortalanmış) dir; ancak Y:Cb:Cr = 4:2:2 olduğunda bu standartta 2 (yan yana) kullanılmasının önerildiği, TV sistemlerinde görüntülendiğinde görüntü kalitesini artırmak içindir. Bu alan mevcut olmadığında, okuyucu TIFF varsayılanını varsaymalıdır. Y:Cb:Cr = 4:2:0 durumunda, TIFF varsayılanı (ortalanmış) önerilir. Okuyucu her iki tür YCbCrPositioning'i destekleme yeteneğine sahip değilse, bu alandaki değere bakılmaksızın TIFF varsayılanını izlemelidir. Okuyucular "<br/>                hem ortalanmış hem de yan yana konumlandırmayı destekleyebilmesi. |
| Y_CB_CR_SUB_SAMPLING | Krominans bileşenlerinin parlaklık bileşenine göre örnekleme oranı. |
| Y_RESOLUTION | ImageLength yönündeki ResolutionUnit başına piksel sayısı. XResolution ile aynı değer atanır. |
