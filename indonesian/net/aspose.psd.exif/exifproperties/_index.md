---
title: "Enum ExifProperties"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.Exif.ExifProperties enum. Daftar tag Exif"
type: docs
weight: 1010
url: /id/net/aspose.psd.exif/exifproperties/
---
{{< psd/tize >}}
## ExifProperties enumeration

Daftar tag Exif

```csharp
public enum ExifProperties : ushort
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| ImageWidth | `256` | Jumlah kolom data gambar, sama dengan jumlah piksel per baris. |
| ImageLength | `257` | Jumlah baris data gambar. |
| BitsPerSample | `258` | Jumlah bit per komponen gambar. Dalam standar ini setiap komponen gambar adalah 8 bit, sehingga nilai untuk tag ini adalah 8. |
| Compression | `259` | Skema kompresi yang digunakan untuk data gambar. Ketika gambar utama dikompresi JPEG, penunjukan ini tidak diperlukan dan dihilangkan. |
| PhotometricInterpretation | `262` | Komposisi piksel. |
| ImageDescription | `270` | String karakter yang memberikan judul gambar. Bisa berupa komentar seperti "1988 company picnic" atau sejenisnya. |
| Make | `271` | Pabrikan peralatan perekaman. Ini adalah pabrikan DSC, pemindai, digitalizer video, atau peralatan lain yang menghasilkan gambar. Ketika bidang ini dibiarkan kosong, dianggap tidak diketahui. |
| Model | `272` | Nama model atau nomor model peralatan. Ini adalah nama atau nomor model DSC, pemindai, digitalizer video, atau peralatan lain yang menghasilkan gambar. Ketika bidang ini dibiarkan kosong, dianggap tidak diketahui. |
| Orientation | `274` | Orientasi gambar yang dilihat dalam istilah baris dan kolom. |
| SamplesPerPixel | `277` | Jumlah komponen per piksel. Karena standar ini berlaku untuk gambar RGB dan YCbCr, nilai yang ditetapkan untuk tag ini adalah 3. |
| XResolution | `282` | Jumlah piksel per ResolutionUnit dalam arah ImageWidth. Ketika resolusi gambar tidak diketahui, ditetapkan 72 [dpi]. |
| YResolution | `283` | Jumlah piksel per ResolutionUnit dalam arah ImageLength. Nilai yang sama dengan XResolution ditetapkan. |
| PlanarConfiguration | `284` | Menunjukkan apakah komponen piksel direkam dalam format chunky atau planar. Jika bidang ini tidak ada, nilai default TIFF 1 (chunky) diasumsikan. |
| ResolutionUnit | `296` | Unit untuk mengukur XResolution dan YResolution. Unit yang sama digunakan untuk XResolution dan YResolution. Jika resolusi gambar tidak diketahui, ditetapkan 2 (inci). |
| TransferFunction | `301` | Fungsi transfer untuk gambar, dijelaskan dalam gaya tabel. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag informasi ruang warna ColorSpace. |
| Software | `305` | Tag ini mencatat nama dan versi perangkat lunak atau firmware kamera atau perangkat input gambar yang digunakan untuk menghasilkan gambar. Format detail tidak ditentukan, tetapi disarankan mengikuti contoh di bawah ini. Ketika bidang ini dibiarkan kosong, dianggap tidak diketahui. |
| DateTime | `306` | Tanggal dan waktu pembuatan gambar. Dalam standar Exif, ini adalah tanggal dan waktu file diubah. |
| Artist | `315` | Tag ini mencatat nama pemilik kamera, fotografer, atau pembuat gambar. Format detail tidak ditentukan, tetapi disarankan agar informasi ditulis seperti contoh di bawah untuk memudahkan interoperabilitas. Ketika bidang ini dibiarkan kosong, dianggap tidak diketahui. Contoh) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| WhitePoint | `318` | Kromatisitas titik putih gambar. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag informasi ruang warna ColorSpace. |
| PrimaryChromaticities | `319` | Kromatisitas tiga warna utama gambar. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag informasi ruang warna ColorSpace. |
| YCbCrCoefficients | `529` | Koefisien matriks untuk transformasi data gambar dari RGB ke YCbCr. |
| YCbCrSubSampling | `530` | Rasio sampling komponen krominansi relatif terhadap komponen luminansi. |
| YCbCrPositioning | `531` | Posisi komponen krominansi relatif terhadap komponen luminansi. Bidang ini hanya ditetapkan untuk data terkompresi JPEG atau data YCbCr yang tidak terkompresi. Default TIFF adalah 1 (terpusat); tetapi ketika Y:Cb:Cr = 4:2:2, standar ini merekomendasikan agar 2 (bersamping) digunakan untuk merekam data, guna meningkatkan kualitas gambar saat ditampilkan pada sistem TV. Ketika bidang ini tidak ada, pembaca harus mengasumsikan default TIFF. Dalam kasus Y:Cb:Cr = 4:2:0, default TIFF (terpusat) direkomendasikan. Jika pembaca tidak memiliki kemampuan mendukung kedua jenis YCbCrPositioning, ia harus mengikuti default TIFF terlepas dari nilai pada bidang ini. Lebih disarankan agar pembaca dapat mendukung baik posisi terpusat maupun bersamping. |
| ReferenceBlackWhite | `532` | Nilai titik hitam referensi dan nilai titik putih referensi. Tidak ada nilai default yang diberikan dalam TIFF, tetapi nilai di bawah ini diberikan sebagai default di sini. Ruang warna dideklarasikan dalam tag informasi ruang warna, dengan default menjadi nilai yang memberikan karakteristik gambar optimal Interoperability kondisi ini. |
| Copyright | `33432` | Informasi hak cipta. Dalam standar ini tag digunakan untuk menunjukkan hak cipta fotografer dan editor. Ini adalah pemberitahuan hak cipta dari orang atau organisasi yang mengklaim hak atas gambar. Pernyataan hak cipta Interoperability termasuk tanggal dan hak harus ditulis dalam bidang ini; misalnya, \"Copyright, John Smith, 19xx. All rights reserved.\". Dalam standar ini bidang mencatat hak cipta fotografer dan editor, masing‑masing dicatat dalam bagian terpisah dari pernyataan. Ketika ada perbedaan yang jelas antara hak cipta fotografer dan editor, keduanya harus ditulis dalam urutan fotografer diikuti oleh hak cipta editor, dipisahkan oleh NULL (dalam kasus ini karena pernyataan juga berakhir dengan NULL, ada dua kode NULL). Ketika hanya hak cipta fotografer yang diberikan, itu diakhiri dengan satu kode NULL. Ketika hanya hak cipta editor yang diberikan, bagian hak cipta fotografer terdiri dari satu spasi diikuti oleh kode NULL penutup, kemudian hak cipta editor diberikan. Ketika bidang dibiarkan kosong, dianggap tidak diketahui. |
| ExposureTime | `33434` | Waktu paparan, diberikan dalam detik. |
| FNumber | `33437` | Angka F. |
| ExposureProgram | `34850` | Kelas program yang digunakan oleh kamera untuk mengatur paparan saat foto diambil. |
| SpectralSensitivity | `34852` | Menunjukkan sensitivitas spektral masing‑masing saluran kamera yang digunakan. |
| PhotographicSensitivity | `34855` | Menunjukkan Kecepatan ISO dan Latitude ISO kamera atau perangkat masukan sebagaimana ditentukan dalam ISO 12232. |
| OECF | `34856` | Menunjukkan Fungsi Konversi Opto‑Elektrik (OECF) yang ditentukan dalam ISO 14524. |
| ExifVersion | `36864` | Versi exif. |
| DateTimeOriginal | `36867` | Tanggal dan waktu ketika data gambar asli dihasilkan. |
| DateTimeDigitized | `36868` | Tanggal dan waktu digitalisasi. |
| ComponentsConfiguration | `37121` | Konfigurasi komponen. |
| CompressedBitsPerPixel | `37122` | Spesifik untuk data terkompresi; menyatakan bit terkompresi per piksel. |
| ShutterSpeedValue | `37377` | Nilai kecepatan rana. |
| ApertureValue | `37378` | Nilai bukaan lensa. |
| BrightnessValue | `37379` | Nilai kecerahan. |
| ExposureBiasValue | `37380` | Nilai bias paparan. |
| MaxApertureValue | `37381` | Nilai bukaan maksimum. |
| SubjectDistance | `37382` | Jarak ke subjek, diberikan dalam meter. |
| MeteringMode | `37383` | Mode pengukuran. |
| LightSource | `37384` | Jenis sumber cahaya. |
| Flash | `37385` | Menunjukkan status lampu kilat ketika gambar diambil. |
| FocalLength | `37386` | Panjang fokus aktual lensa, dalam mm. |
| SubjectArea | `37396` | Tag ini menunjukkan lokasi dan area subjek utama dalam keseluruhan adegan. |
| MakerNote | `37500` | Tag untuk produsen penulis Exif guna merekam informasi apa pun yang diinginkan. Isi tergantung pada produsen, tetapi tag ini tidak boleh digunakan untuk tujuan lain selain yang dimaksudkan. |
| UserComment | `37510` | Tag untuk pengguna Exif menulis kata kunci atau komentar pada gambar selain yang ada di ImageDescription, dan tanpa batasan kode karakter pada tag ImageDescription. |
| SubsecTime | `37520` | Tag yang digunakan untuk merekam pecahan detik untuk tag DateTime. |
| SubsecTimeOriginal | `37521` | Tag yang digunakan untuk merekam pecahan detik untuk tag DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Tag yang digunakan untuk merekam pecahan detik untuk tag DateTimeDigitized. |
| FlashpixVersion | `40960` | Versi format Flashpix yang didukung oleh file FPXR. |
| ColorSpace | `40961` | Tag informasi ruang warna (ColorSpace) selalu dicatat sebagai penunjuk ruang warna. |
| RelatedSoundFile | `40964` | File suara terkait. |
| FlashEnergy | `41483` | Menunjukkan energi strobo pada saat gambar diambil, diukur dalam Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Tag ini mencatat tabel frekuensi spasial kamera atau perangkat input serta nilai SFR dalam arah lebar gambar, tinggi gambar, dan arah diagonal, sebagaimana ditentukan dalam ISO 12233. |
| FocalPlaneXResolution | `41486` | Menunjukkan jumlah piksel dalam arah lebar gambar (X) per FocalPlaneResolutionUnit pada bidang fokus kamera. |
| FocalPlaneYResolution | `41487` | Menunjukkan jumlah piksel dalam arah tinggi gambar (Y) per FocalPlaneResolutionUnit pada bidang fokus kamera. |
| FocalPlaneResolutionUnit | `41488` | Menunjukkan satuan untuk mengukur FocalPlaneXResolution dan FocalPlaneYResolution. Nilai ini sama dengan ResolutionUnit. |
| SubjectLocation | `41492` | Menunjukkan lokasi subjek utama dalam adegan. Nilai tag ini mewakili piksel di tengah subjek utama relatif terhadap tepi kiri, sebelum pemrosesan rotasi sesuai tag Rotation. |
| ExposureIndex | `41493` | Menunjukkan indeks eksposur yang dipilih pada kamera atau perangkat input pada saat gambar diambil. |
| SensingMethod | `41495` | Menunjukkan jenis sensor gambar pada kamera atau perangkat input. |
| FileSource | `41728` | Sumber berkas. |
| SceneType | `41729` | Menunjukkan jenis adegan. Jika DSC merekam gambar, nilai tag ini harus selalu diatur ke 1, menandakan bahwa gambar diambil secara langsung. |
| CFAPattern | `41730` | Menunjukkan pola geometrik array filter warna (CFA) pada sensor gambar ketika sensor area warna satu chip digunakan. Ini tidak berlaku untuk semua metode penginderaan. |
| CustomRendered | `41985` | Tag ini menunjukkan penggunaan pemrosesan khusus pada data gambar, seperti rendering yang disesuaikan untuk output. Ketika pemrosesan khusus dilakukan, pembaca diharapkan menonaktifkan atau meminimalkan pemrosesan lebih lanjut. |
| ExposureMode | `41986` | Tag ini menunjukkan mode eksposur yang diatur saat gambar diambil. Dalam mode auto-bracketing, kamera mengambil serangkaian frame dari adegan yang sama dengan pengaturan eksposur yang berbeda. |
| WhiteBalance | `41987` | Tag ini menunjukkan mode keseimbangan putih yang diatur saat gambar diambil. |
| DigitalZoomRatio | `41988` | Tag ini menunjukkan rasio zoom digital saat gambar diambil. Jika pembilang nilai yang dicatat adalah 0, ini menandakan bahwa zoom digital tidak digunakan. |
| FocalLengthIn35MmFilm | `41989` | Tag ini menunjukkan panjang fokus ekuivalen dengan asumsi kamera film 35mm, dalam mm. Nilai 0 berarti panjang fokus tidak diketahui. Perhatikan bahwa tag ini berbeda dari tag FocalLength. |
| SceneCaptureType | `41990` | Tag ini menunjukkan jenis adegan yang diambil. Ini juga dapat digunakan untuk mencatat mode di mana gambar diambil. |
| GainControl | `41991` | Tag ini menunjukkan tingkat penyesuaian gain keseluruhan gambar. |
| Contrast | `41992` | Tag ini menunjukkan arah pemrosesan kontras yang diterapkan oleh kamera saat gambar diambil. |
| Saturation | `41993` | Tag ini menunjukkan arah pemrosesan saturasi yang diterapkan oleh kamera saat gambar diambil. |
| Sharpness | `41994` | Tag ini menunjukkan arah pemrosesan ketajaman yang diterapkan oleh kamera saat gambar diambil |
| DeviceSettingDescription | `41995` | Tag ini menunjukkan informasi tentang kondisi pengambilan gambar dari model kamera tertentu. Tag ini hanya digunakan untuk menunjukkan kondisi pengambilan gambar di pembaca. |
| SubjectDistanceRange | `41996` | Tag ini menunjukkan jarak ke subjek. |
| ImageUniqueID | `42016` | ID unik gambar. |
| GPSVersionID | `0` | Menunjukkan versi GPSInfoIFD. |
| GPSLatitudeRef | `1` | Menunjukkan apakah lintang berada di utara atau selatan. |
| GPSLatitude | `2` | Menunjukkan lintang. Lintang diekspresikan sebagai tiga nilai RATIONAL yang memberikan derajat, menit, dan detik, masing-masing. Jika lintang diekspresikan sebagai derajat, menit, dan detik, format tipikalnya adalah dd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua tempat desimal, formatnya adalah dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Menunjukkan apakah bujur berada di timur atau barat. |
| GPSLongitude | `4` | Menunjukkan bujur. Bujur diekspresikan sebagai tiga nilai RATIONAL yang memberikan derajat, menit, dan detik, masing-masing. Jika bujur diekspresikan sebagai derajat, menit, dan detik, format tipikalnya adalah ddd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua tempat desimal, formatnya adalah ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Menunjukkan ketinggian yang digunakan sebagai ketinggian referensi. Jika referensinya adalah permukaan laut dan ketinggian di atas permukaan laut, nilai 0 diberikan. Jika ketinggian di bawah permukaan laut, nilai 1 diberikan dan ketinggian ditunjukkan sebagai nilai absolut dalam tag GPSAltitude. |
| GPSAltitude | `6` | Menunjukkan ketinggian berdasarkan referensi di GPSAltitudeRef. Ketinggian diekspresikan sebagai satu nilai RATIONAL. Satuan referensi adalah meter. |
| GPSTimestamp | `7` | Menunjukkan waktu sebagai UTC (Coordinated Universal Time). TimeStamp diekspresikan sebagai tiga nilai RATIONAL yang memberikan jam, menit, dan detik. |
| GPSSatellites | `8` | Menunjukkan satelit GPS yang digunakan untuk pengukuran. Tag ini dapat digunakan untuk menggambarkan jumlah satelit, nomor ID mereka, sudut elevasi, azimut, SNR, dan informasi lain dalam notasi ASCII. Format tidak ditentukan. Jika penerima GPS tidak mampu melakukan pengukuran, nilai tag harus diset ke NULL. |
| GPSStatus | `9` | Menunjukkan status penerima GPS saat gambar direkam. |
| GPSMeasureMode | `10` | Menunjukkan mode pengukuran GPS. - 2- atau 3-dimensi. |
| GPSDOP | `11` | Menunjukkan GPS DOP (data degree of precision). Nilai HDOP ditulis selama pengukuran dua dimensi, dan PDOP selama pengukuran tiga dimensi. |
| GPSSpeedRef | `12` | Menunjukkan satuan yang digunakan untuk mengekspresikan kecepatan pergerakan penerima GPS. 'K', 'M', dan 'N' masing-masing mewakili kilometer per jam, mil per jam, dan knot. |
| GPSSpeed | `13` | Menunjukkan kecepatan pergerakan penerima GPS. |
| GPSTrackRef | `14` | Menunjukkan referensi untuk memberikan arah pergerakan penerima GPS. 'T' menunjukkan arah sejati dan 'M' adalah arah magnetik. |
| GPSTrack | `15` | Menunjukkan arah pergerakan penerima GPS. Rentang nilai adalah dari 0.00 hingga 359.99. |
| GPSImgDirectionRef | `16` | Menunjukkan referensi untuk memberikan arah gambar saat diambil. 'T' menunjukkan arah sejati dan 'M' adalah arah magnetik. |
| GPSImgDirection | `17` | Menunjukkan arah gambar saat diambil. Rentang nilai adalah dari 0.00 hingga 359.99. |
| GPSMapDatum | `18` | Menunjukkan data survei geodetik yang digunakan oleh penerima GPS. |
| GPSDestLatitudeRef | `19` | Menunjukkan apakah lintang titik tujuan berada di lintang utara atau selatan. Nilai ASCII 'N' menunjukkan lintang utara, dan 'S' menunjukkan lintang selatan. |
| GPSDestLatitude | `20` | Menunjukkan lintang titik tujuan. Lintang diekspresikan sebagai tiga nilai RATIONAL yang memberikan derajat, menit, dan detik, masing‑masing. Jika lintang diekspresikan dalam derajat, menit, dan detik, format tipikalnya adalah dd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua tempat desimal, formatnya adalah dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Menunjukkan apakah bujur titik tujuan berada di bujur timur atau barat. ASCII 'E' menunjukkan bujur timur, dan 'W' menunjukkan bujur barat. |
| GPSDestLongitude | `22` | Menunjukkan bujur titik tujuan. Bujur diekspresikan sebagai tiga nilai RATIONAL yang memberikan derajat, menit, dan detik, masing‑masing. Jika bujur diekspresikan dalam derajat, menit, dan detik, format tipikalnya adalah ddd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua tempat desimal, formatnya adalah ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Menunjukkan referensi yang digunakan untuk memberikan arah ke titik tujuan. 'T' menunjukkan arah sejati dan 'M' menunjukkan arah magnetik. |
| GPSDestBearing | `24` | Menunjukkan arah ke titik tujuan. Rentang nilai adalah dari 0.00 hingga 359.99. |
| GPSDestDistanceRef | `25` | Menunjukkan satuan yang digunakan untuk menyatakan jarak ke titik tujuan. 'K', 'M', dan 'N' masing‑masing mewakili kilometer, mil, dan knot. |
| GPSDestDistance | `26` | Menunjukkan jarak ke titik tujuan. |
| GPSProcessingMethod | `27` | String karakter yang merekam nama metode yang digunakan untuk penentuan lokasi. Byte pertama menunjukkan kode karakter yang digunakan, dan diikuti oleh nama metode. |
| GPSAreaInformation | `28` | String karakter yang merekam nama area GPS. Byte pertama menunjukkan kode karakter yang digunakan, dan diikuti oleh nama area GPS. |
| GPSDateStamp | `29` | String karakter yang merekam informasi tanggal dan waktu relatif terhadap UTC (Coordinated Universal Time). Formatnya adalah YYYY:MM:DD. |
| GPSDifferential | `30` | Menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS. |
| StripOffsets | `273` | Untuk setiap strip, offset byte dari strip tersebut. Disarankan agar dipilih sehingga jumlah byte strip tidak melebihi 64 Kbyte. Tag aux. |
| JPEGInterchangeFormat | `513` | Offset ke byte awal (SOI) data thumbnail terkompres JPEG. Ini tidak digunakan untuk data JPEG gambar utama. |
| JPEGInterchangeFormatLength | `514` | Jumlah byte data thumbnail terkompres JPEG. Ini tidak digunakan untuk data JPEG gambar utama. Thumbnail JPEG tidak dibagi tetapi direkam sebagai aliran bit JPEG kontinu dari SOI ke EOI. Penanda Appn dan COM tidak boleh direkam. Thumbnail terkompres harus direkam tidak lebih dari 64 Kbyte, termasuk semua data lain yang akan direkam di APP1. |
| ExifIfdPointer | `34665` | Penunjuk ke Exif IFD. Interoperabilitas, Exif IFD memiliki struktur yang sama dengan IFD yang ditentukan dalam TIFF. Namun, biasanya tidak berisi data gambar seperti pada TIFF. |
| GPSIfdPointer | `34853` | Penunjuk gps ifd. |
| RowsPerStrip | `278` | Jumlah baris per strip. Ini adalah jumlah baris dalam gambar satu strip ketika gambar dibagi menjadi strip. |
| StripByteCounts | `279` | Jumlah total byte dalam setiap strip. |
| PixelXDimension | `40962` | Informasi khusus untuk data terkompres. Ketika file terkompres direkam, lebar valid dari gambar yang bermakna harus direkam dalam tag ini, terlepas apakah ada data padding atau penanda restart. |
| PixelYDimension | `40963` | Informasi khusus untuk data terkompres. Ketika file terkompres direkam, tinggi valid dari gambar yang bermakna harus direkam dalam tag ini. |
| Gamma | `42240` | Nilai gamma |
| SensitivityType | `34864` | Jenis sensitivitas fotografi |
| StandardOutputSensitivity | `34865` | Menunjukkan sensitivitas output standar kamera |
| RecommendedExposureIndex | `34866` | Menunjukkan indeks eksposur yang direkomendasikan |
| ISOSpeed | `34867` | Informasi tentang nilai kecepatan iso sebagaimana didefinisikan dalam ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Tag ini menunjukkan nilai latitude kecepatan ISO yyy sebagaimana didefinisikan dalam ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Tag ini menunjukkan nilai latitude kecepatan ISO zzz sebagaimana didefinisikan dalam ISO 12232 |
| CameraOwnerName | `42032` | Berisi nama pemilik kamera |
| BodySerialNumber | `42033` | Berisi nomor seri bodi kamera |
| LensMake | `42035` | Tag ini mencatat produsen lensa |
| LensModel | `42036` | Tag ini mencatat nama model lensa dan nomor modelnya |
| LensSerialNumber | `42037` | Tag ini mencatat nomor seri lensa yang dapat dipertukarkan |
| LensSpecification | `42034` | Tag ini mencatat panjang fokus minimum, panjang fokus maksimum, angka F minimum pada panjang fokus minimum, dan angka F minimum pada panjang fokus maksimum |

### Lihat Juga

* namespace [Aspose.PSD.Exif](../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../)


