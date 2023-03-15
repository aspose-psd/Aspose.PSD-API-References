---
title: Enum ExifProperties
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Exif.ExifProperties enum. Daftar tag exif
type: docs
weight: 1000
url: /id/net/aspose.psd.exif/exifproperties/
---
## ExifProperties enumeration

Daftar tag exif

```csharp
public enum ExifProperties : ushort
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| ImageWidth | `256` | Jumlah kolom data gambar, sama dengan jumlah piksel per baris. |
| ImageLength | `257` | Jumlah baris data gambar. |
| BitsPerSample | `258` | Jumlah bit per komponen gambar. Dalam standar ini setiap komponen gambar berukuran 8 bit, sehingga nilai tag ini adalah 8. |
| Compression | `259` | Skema kompresi yang digunakan untuk data gambar. Saat gambar utama dikompresi JPEG, penunjukan ini tidak diperlukan dan dihilangkan. |
| PhotometricInterpretation | `262` | Komposisi piksel. |
| ImageDescription | `270` | String karakter yang memberikan judul gambar. Mungkin berupa komentar seperti "piknik perusahaan tahun 1988" atau sejenisnya. |
| Make | `271` | Produsen peralatan rekaman. Ini adalah pabrikan DSC, pemindai, digitizer video, atau peralatan lain yang menghasilkan gambar. Jika bidang dibiarkan kosong, bidang tersebut dianggap tidak diketahui. |
| Model | `272` | Nama model atau nomor model peralatan. Ini adalah nama model atau nomor DSC, pemindai, digitizer video, atau peralatan lain yang menghasilkan gambar. Jika bidang dibiarkan kosong, bidang tersebut dianggap tidak diketahui. |
| Orientation | `274` | Orientasi gambar dilihat dalam baris dan kolom. |
| SamplesPerPixel | `277` | Jumlah komponen per piksel. Karena standar ini berlaku untuk gambar RGB dan YCbCr, nilai yang ditetapkan untuk tag ini adalah 3. |
| XResolution | `282` | Jumlah piksel per Unit Resolusi dalam arah ImageWidth. Saat resolusi gambar tidak diketahui, ditetapkan 72 [dpi]. |
| YResolution | `283` | Jumlah piksel per Unit Resolusi dalam arah ImageLength. Nilai yang sama dengan XResolution ditetapkan. |
| PlanarConfiguration | `284` | Menunjukkan apakah komponen piksel direkam dalam format chunky atau planar. Jika bidang ini tidak ada, default TIFF 1 (chunky) diasumsikan. |
| ResolutionUnit | `296` | Satuan untuk mengukur XResolution dan YResolution. Unit yang sama digunakan untuk XResolution dan YResolution. Jika resolusi gambar tidak diketahui, 2 (inci) ditetapkan. |
| TransferFunction | `301` | Fungsi transfer untuk gambar, dijelaskan dalam gaya tabel. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag ColorSpace informasi ruang warna. |
| Software | `305` | Tag ini merekam nama dan versi perangkat lunak atau firmware kamera atau perangkat input gambar yang digunakan untuk menghasilkan gambar. Format terperinci tidak ditentukan, tetapi disarankan untuk mengikuti contoh yang ditunjukkan di bawah ini. Jika bidang dibiarkan kosong, bidang tersebut dianggap tidak diketahui. |
| DateTime | `306` | Tanggal dan waktu pembuatan gambar. Dalam standar Exif, ini adalah tanggal dan waktu file diubah. |
| Artist | `315` | Tag ini mencatat nama pemilik kamera, fotografer atau pembuat gambar. Format detailnya tidak ditentukan, namun disarankan agar informasinya ditulis seperti pada contoh di bawah ini untuk kemudahan interoperabilitas. Ketika bidang dibiarkan kosong, itu diperlakukan sebagai tidak diketahui. Mis.) "Pemilik kamera, John Smith; Fotografer, Michael Brown; Pembuat gambar, Ken James" |
| WhitePoint | `318` | Kromatisitas titik putih gambar. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag ColorSpace informasi ruang warna. |
| PrimaryChromaticities | `319` | Kromatisitas dari tiga warna primer gambar. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag ColorSpace informasi ruang warna. |
| YCbCrCoefficients | `529` | Koefisien matriks untuk transformasi dari data citra RGB ke YCbCr. |
| YCbCrSubSampling | `530` | Rasio sampling komponen chrominance terkait dengan komponen luminance. |
| YCbCrPositioning | `531` | Posisi komponen chrominance dalam kaitannya dengan komponen luminance . Kolom ini ditujukan hanya untuk data terkompresi JPEG atau data YCbCr tidak terkompresi. Standar TIFF adalah 1 (tengah); tetapi ketika Y:Cb:Cr = 4:2:2, maka direkomendasikan dalam standar ini bahwa 2 (co-sited) digunakan untuk merekam data, untuk meningkatkan kualitas gambar saat dilihat pada sistem TV. Jika kolom ini tidak ada, pembaca shall menganggap default TIFF. Dalam kasus Y:Cb:Cr = 4:2:0, the TIFF default (di tengah) direkomendasikan. Jika reader tidak memiliki kemampuan untuk mendukung kedua jenis YCbCrPositioning, maka akan mengikuti default TIFF terlepas dari nilai di bidang ini. Sebaiknya pembaca " dapat mendukung pemosisian terpusat dan bersama. |
| ReferenceBlackWhite | `532` | Nilai titik hitam referensi dan nilai titik putih referensi . Tidak ada default yang diberikan di TIFF, tetapi nilai di bawah ini diberikan sebagai default di sini. Ruang warna dinyatakan dalam tag informasi ruang warna, dengan default menjadi nilai yang memberikan karakteristik gambar yang optimal Interoperabilitas kondisi ini |
| Copyright | `33432` | Informasi hak cipta. Dalam standar ini, tag digunakan untuk menunjukkan hak cipta fotografer dan editor. Ini adalah pemberitahuan hak cipta dari orang atau organisasi yang mengklaim hak atas gambar tersebut. Pernyataan hak cipta Interoperabilitas termasuk tanggal dan hak harus ditulis di bidang ini; misalnya, "Hak Cipta, John Smith, 19xx. Semua hak dilindungi undang-undang.". Dalam standar ini, bidang mencatat baik hak cipta fotografer dan editor , dengan masing-masing direkam dalam a bagian terpisah dari pernyataan tersebut. Ketika ada perbedaan yang jelas antara hak cipta fotografer dan editor, ini harus ditulis dalam urutan fotografer diikuti dengan hak cipta editor, dipisahkan oleh NULL (dalam hal ini karena pernyataan juga diakhiri dengan NULL, ada dua kode NULL ). Ketika hanya hak cipta photographer yang diberikan, itu diakhiri dengan satu kode NULL . Ketika hanya hak cipta editor yang diberikan, bagian hak cipta fotografer terdiri dari satu spasi diikuti dengan kode NULL terminasi, kemudian hak cipta editor diberikan. Saat kolom dibiarkan kosong, kolom tersebut diperlakukan sebagai tidak diketahui. |
| ExposureTime | `33434` | Waktu pemaparan, diberikan dalam hitungan detik. |
| FNumber | `33437` | Angka F. |
| ExposureProgram | `34850` | Kelas program yang digunakan kamera untuk menyetel eksposur saat gambar diambil. |
| SpectralSensitivity | `34852` | Menunjukkan sensitivitas spektral dari setiap saluran kamera yang digunakan. |
| PhotographicSensitivity | `34855` | Menunjukkan ISO Speed dan ISO Latitude kamera atau perangkat input seperti yang ditentukan dalam ISO 12232. |
| OECF | `34856` | Menunjukkan Fungsi Konversi Opto-Listrik (OECF) yang ditentukan dalam ISO 14524. |
| ExifVersion | `36864` | Versi exif. |
| DateTimeOriginal | `36867` | Tanggal dan waktu pembuatan data gambar asli. |
| DateTimeDigitized | `36868` | Waktu tanggal didigitalkan. |
| ComponentsConfiguration | `37121` | Konfigurasi komponen. |
| CompressedBitsPerPixel | `37122` | Khusus untuk data terkompresi; menyatakan bit terkompresi per piksel. |
| ShutterSpeedValue | `37377` | Nilai kecepatan rana. |
| ApertureValue | `37378` | Nilai apertur lensa. |
| BrightnessValue | `37379` | Nilai kecerahan. |
| ExposureBiasValue | `37380` | Nilai bias paparan. |
| MaxApertureValue | `37381` | Nilai apertur maks. |
| SubjectDistance | `37382` | Jarak ke subjek, diberikan dalam meter. |
| MeteringMode | `37383` | Mode pengukuran. |
| LightSource | `37384` | Jenis sumber cahaya. |
| Flash | `37385` | Menunjukkan status lampu kilat saat gambar diambil. |
| FocalLength | `37386` | Panjang fokus sebenarnya dari lensa, dalam mm. |
| SubjectArea | `37396` | Tag ini menunjukkan lokasi dan area subjek utama dalam pemandangan keseluruhan. |
| MakerNote | `37500` | Tag untuk produsen penulis Exif untuk merekam informasi yang diinginkan. Konten terserah produsen, tetapi tag ini tidak boleh digunakan selain untuk tujuan yang dimaksudkan. |
| UserComment | `37510` | Tag untuk pengguna Exif untuk menulis kata kunci atau komentar pada gambar selain yang ada di ImageDescription, dan tanpa batasan kode karakter dari tag ImageDescription. |
| SubsecTime | `37520` | Tag yang digunakan untuk merekam sepersekian detik untuk tag DateTime. |
| SubsecTimeOriginal | `37521` | Tag yang digunakan untuk merekam sepersekian detik untuk tag DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Tag yang digunakan untuk merekam sepersekian detik untuk tag DateTimeDigitized. |
| FlashpixVersion | `40960` | Versi format Flashpix didukung oleh file FPXR. |
| ColorSpace | `40961` | Tag informasi ruang warna (ColorSpace) selalu direkam sebagai penentu ruang warna. |
| RelatedSoundFile | `40964` | File suara terkait. |
| FlashEnergy | `41483` | Menunjukkan energi strobo pada saat gambar diambil, yang diukur dalam Beam Candle Power Seconds(BCPS). |
| SpatialFrequencyResponse | `41484` | Tag ini merekam tabel frekuensi spasial kamera atau perangkat masukan dan nilai SFR dalam arah lebar gambar, tinggi gambar, dan arah diagonal, sebagaimana ditentukan dalam ISO 12233. |
| FocalPlaneXResolution | `41486` | Menunjukkan jumlah piksel dalam arah lebar gambar (X) per FocalPlaneResolutionUnit pada bidang fokus kamera. |
| FocalPlaneYResolution | `41487` | Menunjukkan jumlah piksel dalam arah tinggi gambar (Y) per FocalPlaneResolutionUnit pada bidang fokus kamera. |
| FocalPlaneResolutionUnit | `41488` | Menunjukkan unit untuk mengukur FocalPlaneXResolution dan FocalPlaneYResolution. Nilai ini sama dengan ResolutionUnit. |
| SubjectLocation | `41492` | Menunjukkan lokasi subjek utama dalam pemandangan. Nilai tag ini mewakili piksel di tengah subjek utama relatif terhadap tepi kiri, sebelum pemrosesan rotasi sesuai tag Rotasi. |
| ExposureIndex | `41493` | Menunjukkan indeks eksposur yang dipilih pada kamera atau perangkat input pada saat pengambilan gambar. |
| SensingMethod | `41495` | Menunjukkan jenis sensor gambar pada kamera atau perangkat masukan. |
| FileSource | `41728` | Sumber file. |
| SceneType | `41729` | Menunjukkan jenis adegan. Jika DSC merekam gambar tersebut, nilai tag ini harus selalu disetel ke 1, yang menunjukkan bahwa gambar tersebut langsung difoto. |
| CFAPattern | `41730` | Menunjukkan pola geometris susunan filter warna (CFA) dari sensor gambar saat sensor area warna satu chip digunakan. Itu tidak berlaku untuk semua metode penginderaan. |
| CustomRendered | `41985` | Tag ini menunjukkan penggunaan pemrosesan khusus pada data gambar, seperti rendering yang diarahkan ke keluaran. Saat pemrosesan khusus dilakukan, pembaca diharapkan menonaktifkan atau meminimalkan pemrosesan lebih lanjut. |
| ExposureMode | `41986` | Tag ini menunjukkan mode eksposur yang diatur saat gambar diambil. Dalam mode auto-bracketing, kamera memotret rangkaian frame dari pemandangan yang sama pada pengaturan eksposur yang berbeda. |
| WhiteBalance | `41987` | Tag ini menunjukkan mode keseimbangan putih yang disetel saat gambar diambil. |
| DigitalZoomRatio | `41988` | Tag ini menunjukkan rasio pembesaran digital saat gambar diambil. Jika pembilang dari nilai yang direkam adalah 0, ini menunjukkan bahwa zoom digital tidak digunakan. |
| FocalLengthIn35MmFilm | `41989` | Tag ini menunjukkan panjang fokus setara dengan asumsi kamera film 35mm, dalam mm. Nilai 0 berarti panjang fokus tidak diketahui. Perhatikan bahwa tag ini berbeda dengan tag FocalLength. |
| SceneCaptureType | `41990` | Tag ini menunjukkan jenis adegan yang diambil. Itu juga dapat digunakan untuk merekam mode pengambilan gambar. |
| GainControl | `41991` | Tag ini menunjukkan tingkat penyesuaian perolehan gambar secara keseluruhan. |
| Contrast | `41992` | Tag ini menunjukkan arah pemrosesan kontras yang diterapkan oleh kamera saat gambar diambil. |
| Saturation | `41993` | Tag ini menunjukkan arah pemrosesan saturasi yang diterapkan oleh kamera saat gambar diambil. |
| Sharpness | `41994` | Tag ini menunjukkan arah pemrosesan ketajaman yang diterapkan oleh kamera saat gambar diambil |
| DeviceSettingDescription | `41995` | Tag ini menunjukkan informasi tentang kondisi pengambilan gambar model kamera tertentu. Tag hanya digunakan untuk menunjukkan kondisi pengambilan gambar di reader. |
| SubjectDistanceRange | `41996` | Tag ini menunjukkan jarak ke subjek. |
| ImageUniqueID | `42016` | Id unik gambar. |
| GPSVersionID | `0` | Menunjukkan versi GPSInfoIFD. |
| GPSLatitudeRef | `1` | Menunjukkan apakah lintang utara atau lintang selatan. |
| GPSLatitude | `2` | Menunjukkan garis lintang. Garis lintang dinyatakan sebagai tiga nilai RATIONAL yang masing-masing memberikan derajat, menit, dan detik. Jika garis lintang dinyatakan sebagai derajat, menit, dan detik, format umumnya adalah dd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua tempat desimal, formatnya akan menjadi dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Menunjukkan apakah bujur timur atau bujur barat. |
| GPSLongitude | `4` | Menunjukkan garis bujur. Garis bujur dinyatakan sebagai tiga nilai RATIONAL yang masing-masing memberikan derajat, menit, dan detik. Jika bujur dinyatakan sebagai derajat, menit, dan detik, format biasanya adalah ddd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua tempat desimal, formatnya akan menjadi ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Menunjukkan ketinggian yang digunakan sebagai ketinggian referensi. Jika acuannya adalah permukaan laut dan ketinggiannya di atas permukaan laut, diberikan 0. Jika ketinggian berada di bawah permukaan laut, nilai 1 diberikan dan ketinggian ditunjukkan sebagai nilai absolut dalam tag GPSAltitude. |
| GPSAltitude | `6` | Menunjukkan ketinggian berdasarkan referensi di GPSAltitudeRef. Ketinggian dinyatakan sebagai satu nilai RATIONAL. Satuan acuannya adalah meter. |
| GPSTimestamp | `7` | Menunjukkan waktu sebagai UTC (Waktu Universal Terkoordinasi). TimeStamp dinyatakan sebagai tiga nilai RATIONAL memberikan jam, menit, dan detik. |
| GPSSatellites | `8` | Menunjukkan satelit GPS yang digunakan untuk pengukuran. Tag ini dapat digunakan untuk menggambarkan jumlah satelit, nomor ID mereka, sudut elevasi, azimuth, SNR dan informasi lainnya dalam notasi ASCII. Formatnya tidak ditentukan. Jika penerima GPS tidak mampu melakukan pengukuran, nilai tag harus disetel ke NULL. |
| GPSStatus | `9` | Menunjukkan status penerima GPS saat gambar direkam. |
| GPSMeasureMode | `10` | Menunjukkan mode pengukuran GPS. - 2- atau 3-dimensi. |
| GPSDOP | `11` | Menunjukkan GPS DOP (tingkat presisi data). Nilai HDOP ditulis selama pengukuran dua dimensi, dan PDOP selama pengukuran tiga dimensi. |
| GPSSpeedRef | `12` | Menunjukkan unit yang digunakan untuk menyatakan kecepatan gerakan penerima GPS. 'K' 'M' dan 'N' mewakili kilometer per jam, mil per jam, dan knot. |
| GPSSpeed | `13` | Menunjukkan kecepatan pergerakan penerima GPS. |
| GPSTrackRef | `14` | Menunjukkan referensi untuk memberikan arah pergerakan penerima GPS. 'T' menunjukkan arah yang benar dan 'M' adalah arah magnet. |
| GPSTrack | `15` | Menunjukkan arah pergerakan penerima GPS. Rentang nilainya adalah dari 0,00 hingga 359,99. |
| GPSImgDirectionRef | `16` | Menunjukkan referensi untuk memberikan arah gambar saat diambil. 'T' menunjukkan arah yang benar dan 'M' adalah arah magnet. |
| GPSImgDirection | `17` | Menunjukkan arah gambar saat diambil. Rentang nilainya adalah dari 0,00 hingga 359,99. |
| GPSMapDatum | `18` | Menunjukkan data survei geodetik yang digunakan oleh penerima GPS. |
| GPSDestLatitudeRef | `19` | Menunjukkan apakah garis lintang titik tujuan adalah garis lintang utara atau selatan. Nilai ASCII 'N' menunjukkan lintang utara , dan 'S' adalah lintang selatan. |
| GPSDestLatitude | `20` | Menunjukkan garis lintang titik tujuan. Garis lintang dinyatakan sebagai tiga nilai RATIONAL yang masing-masing memberikan derajat, menit, dan detik. Jika garis lintang dinyatakan sebagai derajat, menit, dan detik, format tipikal adalah dd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit adalah diberikan hingga dua tempat desimal, formatnya akan menjadi dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Menunjukkan apakah bujur titik tujuan adalah bujur timur atau bujur barat. ASCII 'E' menunjukkan bujur timur, dan 'W' adalah bujur barat. |
| GPSDestLongitude | `22` | Menunjukkan bujur titik tujuan. Garis bujur dinyatakan sebagai tiga nilai RATIONAL yang masing-masing memberikan derajat, menit, dan detik. Jika garis bujur dinyatakan sebagai derajat, menit, dan detik, format tipikal adalah ddd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit adalah diberikan hingga dua tempat desimal, formatnya akan menjadi ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Menunjukkan referensi yang digunakan untuk memberikan bantalan ke titik tujuan. 'T' menunjukkan arah yang benar dan 'M' adalah arah magnet. |
| GPSDestBearing | `24` | Menunjukkan bantalan ke titik tujuan. Rentang nilainya adalah dari 0,00 hingga 359,99. |
| GPSDestDistanceRef | `25` | Menunjukkan satuan yang digunakan untuk menyatakan jarak ke titik tujuan. 'K', 'M' dan 'N' mewakili kilometer, miles dan knot. |
| GPSDestDistance | `26` | Menunjukkan jarak ke titik tujuan. |
| GPSProcessingMethod | `27` | String karakter yang merekam nama metode yang digunakan untuk pencarian lokasi. Byte pertama menunjukkan kode karakter yang digunakan, diikuti dengan nama metode. |
| GPSAreaInformation | `28` | String karakter yang merekam nama area GPS. Byte pertama menunjukkan kode karakter yang digunakan, diikuti dengan nama area GPS. |
| GPSDateStamp | `29` | Informasi tanggal dan waktu perekaman string karakter relatif terhadap UTC (Waktu Universal Terkoordinasi). Formatnya YYYY:MM:DD. |
| GPSDifferential | `30` | Menunjukkan apakah koreksi diferensial diterapkan ke penerima GPS. |
| StripOffsets | `273` | Untuk setiap strip, offset byte dari strip tersebut. Direkomendasikan agar ini dipilih sehingga jumlah byte strip tidak melebihi 64 Kbytes. Aux tag. |
| JPEGInterchangeFormat | `513` | Offset ke byte awal (SOI) dari data thumbnail terkompresi JPEG. Ini tidak digunakan untuk data JPEG gambar utama. |
| JPEGInterchangeFormatLength | `514` | Jumlah byte data thumbnail terkompresi JPEG. Ini tidak digunakan untuk data JPEG gambar utama. Thumbnail JPEG tidak dibagi tetapi direkam sebagai bitstream JPEG berkelanjutan dari SOI ke EOI. Penanda Appn dan COM tidak boleh direkam. Thumbnail terkompresi harus direkam tidak lebih dari 64 Kbytes, termasuk semua data lain yang akan direkam dalam APP1. |
| ExifIfdPointer | `34665` | Penunjuk ke IFD Exif. Interoperabilitas, Exif IFD memiliki struktur yang sama dengan IFD yang ditentukan dalam TIFF. namun biasanya tidak berisi data gambar seperti pada kasus TIFF. |
| GPSIfdPointer | `34853` | Penunjuk ifd gps. |
| RowsPerStrip | `278` | Jumlah baris per strip. Ini adalah jumlah baris pada gambar dari satu strip saat gambar dibagi menjadi beberapa strip. |
| StripByteCounts | `279` | Jumlah total byte di setiap strip. |
| PixelXDimension | `40962` | Informasi khusus untuk data terkompresi. Saat file terkompresi direkam, lebar valid dari gambar bermakna harus direkam dalam tag ini, terlepas dari apakah ada data padding atau penanda mulai ulang. |
| PixelYDimension | `40963` | Informasi khusus untuk data terkompresi. Saat file terkompresi direkam, ketinggian valid dari gambar bermakna harus direkam dalam tag ini |
| Gamma | `42240` | Nilai gamma |
| SensitivityType | `34864` | Jenis kepekaan fotografis |
| StandardOutputSensitivity | `34865` | Menunjukkan sensitivitas keluaran standar kamera |
| RecommendedExposureIndex | `34866` | Menunjukkan indeks keterpaparan yang disarankan |
| ISOSpeed | `34867` | Informasi tentang nilai kecepatan iso sebagaimana ditentukan dalam ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Tag ini menunjukkan nilai ISO speed latitude yyy seperti yang didefinisikan dalam ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Tag ini menunjukkan nilai zzz garis lintang kecepatan ISO sebagaimana ditentukan dalam ISO 12232 |
| CameraOwnerName | `42032` | Berisi nama pemilik kamera |
| BodySerialNumber | `42033` | Berisi nomor seri bodi kamera |
| LensMake | `42035` | Tag ini merekam pabrikan lensa |
| LensModel | `42036` | Tag ini merekam nama model dan nomor model lensa |
| LensSerialNumber | `42037` | Tag ini mencatat nomor seri lensa yang dapat dipertukarkan |
| LensSpecification | `42034` | Tag ini mencatat panjang fokus minimum, panjang fokus maksimum, angka F minimum pada panjang fokus minimum dan angka F minimum pada panjang fokus maksimum |

### Lihat juga

* ruang nama [Aspose.PSD.Exif](../../aspose.psd.exif/)
* perakitan [Aspose.PSD](../../)


