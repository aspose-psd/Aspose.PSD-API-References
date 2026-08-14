---
title: "Enumerasi ExifProperties"
type: docs
weight: 160
url: /id/python-net/aspose.psd.exif/exifproperties/
---

Daftar tag Exif

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifProperties

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Nama anggota** | **Deskripsi** |
| :- | :- |
| APERTURE_VALUE | Nilai bukaan lensa. |
| ARTIST | Tag ini mencatat nama pemilik kamera, fotografer, atau pembuat gambar. Format detail tidak ditentukan, tetapi disarankan agar informasi ditulis seperti contoh di bawah untuk memudahkan interoperabilitas. Ketika bidang ini dibiarkan kosong, dianggap tidak diketahui. Contoh: "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | Jumlah bit per komponen gambar. Dalam standar ini setiap komponen gambar memiliki 8 bit, sehingga nilai untuk tag ini adalah 8. |
| BODY_SERIAL_NUMBER | Berisi nomor seri bodi kamera |
| BRIGHTNESS_VALUE | Nilai kecerahan. |
| CAMERA_OWNER_NAME | Berisi nama pemilik kamera |
| CFA_PATTERN | Menunjukkan pola geometrik array filter warna (CFA) pada sensor gambar ketika sensor area warna satu chip digunakan. Tidak berlaku untuk semua metode penginderaan. |
| COLOR_SPACE | Tag informasi ruang warna (ColorSpace) selalu dicatat sebagai penunjuk ruang warna. |
| COMPONENTS_CONFIGURATION | Konfigurasi komponen. |
| COMPRESSED_BITS_PER_PIXEL | Spesifik untuk data terkompresi; menyatakan bit terkompresi per piksel. |
| COMPRESSION | Skema kompresi yang digunakan untuk data gambar. Ketika gambar utama dikompresi JPEG, penunjukan ini tidak diperlukan dan dihilangkan. |
| CONTRAST | Tag ini menunjukkan arah pemrosesan kontras yang diterapkan oleh kamera saat gambar diambil. |
| COPYRIGHT | Informasi hak cipta. Dalam standar ini tag ini digunakan untuk<br/>                menunjukkan hak cipta fotografer dan editor. Ini adalah<br/>                pemberitahuan hak cipta dari orang atau organisasi yang mengklaim<br/>                hak atas gambar. Pernyataan hak cipta Interoperabilitas<br/>                yang mencakup tanggal dan hak harus ditulis dalam field; misalnya, "Copyright, John Smith, 19xx. Semua hak<br/>                dilindungi.". Dalam standar ini field mencatat kedua<br/>                hak cipta fotografer dan editor, dengan masing-masing dicatat dalam sebuah<br/>                bagian terpisah dari pernyataan. Ketika ada perbedaan jelas<br/>                antara hak cipta fotografer dan editor, ini harus ditulis dalam urutan fotografer diikuti oleh hak cipta editor,<br/>                dipisahkan oleh NULL (dalam kasus ini karena pernyataan juga berakhir dengan<br/>                sebuah NULL, ada dua kode NULL). Ketika hanya hak cipta fotografer<br/>                yang diberikan, diakhiri dengan satu kode NULL . Ketika hanya<br/>                hak cipta editor yang diberikan, bagian hak cipta fotografer<br/>                terdiri dari satu spasi diikuti oleh kode NULL penutup, kemudian<br/>                hak cipta editor diberikan. Ketika field dibiarkan kosong, itu<br/>                dianggap tidak diketahui. |
| CUSTOM_RENDERED | Tag ini menunjukkan penggunaan pemrosesan khusus pada data gambar, seperti rendering yang diarahkan ke output. Ketika pemrosesan khusus dilakukan, pembaca diharapkan untuk menonaktifkan atau meminimalkan pemrosesan lebih lanjut. |
| DATE_TIME | Tanggal dan waktu pembuatan gambar. Dalam standar Exif, ini adalah tanggal dan waktu file diubah. |
| DATE_TIME_DIGITIZED | Tanggal dan waktu digitasi. |
| DATE_TIME_ORIGINAL | Tanggal dan waktu saat data gambar asli dihasilkan. |
| DEVICE_SETTING_DESCRIPTION | Tag ini menunjukkan informasi tentang kondisi pengambilan gambar dari model kamera tertentu. Tag ini hanya digunakan untuk menunjukkan kondisi pengambilan gambar di pembaca. |
| DIGITAL_ZOOM_RATIO | Tag ini menunjukkan rasio zoom digital saat gambar diambil. Jika pembilang nilai yang tercatat adalah 0, ini menunjukkan bahwa zoom digital tidak digunakan. |
| EXIF_IFD_POINTER | Penunjuk ke Exif IFD. Interoperabilitas, Exif IFD memiliki struktur yang sama dengan IFD yang ditentukan dalam TIFF. Namun, biasanya tidak berisi data gambar seperti pada TIFF. |
| EXIF_VERSION | Versi exif. |
| EXPOSURE_BIAS_VALUE | Nilai bias eksposur. |
| EXPOSURE_INDEX | Menunjukkan indeks eksposur yang dipilih pada kamera atau perangkat input pada saat gambar diambil. |
| EXPOSURE_MODE | Tag ini menunjukkan mode eksposur yang diatur saat gambar diambil. Dalam mode auto-bracketing, kamera mengambil serangkaian frame dari adegan yang sama dengan pengaturan eksposur yang berbeda. |
| EXPOSURE_PROGRAM | Kelas program yang digunakan oleh kamera untuk mengatur eksposur saat gambar diambil. |
| EXPOSURE_TIME | Waktu paparan, diberikan dalam detik. |
| FILE_SOURCE | Sumber berkas. |
| FLASH | Menunjukkan status lampu kilat saat gambar diambil. |
| FLASHPIX_VERSION | Versi format Flashpix yang didukung oleh berkas FPXR. |
| FLASH_ENERGY | Menunjukkan energi strobo pada saat gambar diambil, diukur dalam Beam Candle Power Seconds (BCPS). |
| FOCAL_LENGTH | Panjang fokus sebenarnya dari lensa, dalam mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | Tag ini menunjukkan panjang fokus ekuivalen dengan asumsi kamera film 35mm, dalam mm. Nilai 0 berarti panjang fokus tidak diketahui. Perhatikan bahwa tag ini berbeda dari tag FocalLength. |
| FOCAL_PLANE_RESOLUTION_UNIT | Menunjukkan satuan untuk mengukur FocalPlaneXResolution dan FocalPlaneYResolution. Nilai ini sama dengan ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Menunjukkan jumlah piksel pada lebar gambar (X) per FocalPlaneResolutionUnit pada bidang fokus kamera. |
| FOCAL_PLANE_Y_RESOLUTION | Menunjukkan jumlah piksel pada tinggi gambar (Y) per FocalPlaneResolutionUnit pada bidang fokus kamera. |
| F_NUMBER | Angka F. |
| GAIN_CONTROL | Tag ini menunjukkan tingkat penyesuaian gain keseluruhan gambar. |
| GAMMA | Nilai gamma |
| GPSDOP | Menunjukkan GPS DOP (data degree of precision). Nilai HDOP ditulis selama pengukuran dua dimensi,<br/>                dan PDOP selama pengukuran tiga dimensi. |
| GPS_ALTITUDE | Menunjukkan ketinggian berdasarkan referensi di GPSAltitudeRef. Ketinggian dinyatakan sebagai satu nilai RATIONAL.<br/>                Satuan referensi adalah meter. |
| GPS_ALTITUDE_REF | Menunjukkan ketinggian yang digunakan sebagai ketinggian referensi. Jika referensinya adalah permukaan laut dan ketinggian berada di atas permukaan laut,<br/>                nilai 0 diberikan. Jika ketinggian berada di bawah permukaan laut, nilai 1 diberikan dan ketinggian ditunjukkan sebagai nilai absolut dalam<br/>                tag GPSAltitude. |
| GPS_AREA_INFORMATION | String karakter yang merekam nama area GPS. Byte pertama menunjukkan<br/>                kode karakter yang digunakan, dan diikuti oleh nama area GPS. |
| GPS_DATE_STAMP | String karakter yang merekam informasi tanggal dan waktu relatif terhadap UTC<br/>                (Coordinated Universal Time). Formatnya adalah YYYY:MM:DD. |
| GPS_DEST_BEARING | Menunjukkan arah (bearing) ke titik tujuan. Rentang nilai adalah dari 0.00 hingga 359.99. |
| GPS_DEST_BEARING_REF | Menunjukkan referensi yang digunakan untuk memberikan arah ke titik tujuan. 'T' menunjukkan arah sejati dan 'M' adalah<br/>                arah magnetik. |
| GPS_DEST_DISTANCE | Menunjukkan jarak ke titik tujuan. |
| GPS_DEST_DISTANCE_REF | Menunjukkan satuan yang digunakan untuk menyatakan jarak ke titik tujuan. 'K', 'M', dan 'N' masing-masing mewakili kilometer, mil<br/>                dan knot. |
| GPS_DEST_LATITUDE | Menunjukkan lintang titik tujuan. Lintang dinyatakan sebagai tiga nilai RATIONAL yang memberikan<br/>                derajat, menit, dan detik, masing-masing. Jika lintang dinyatakan dalam derajat, menit, dan detik, format tipikalnya adalah dd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua tempat desimal, formatnya menjadi dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Menunjukkan apakah lintang titik tujuan adalah lintang utara atau selatan. Nilai ASCII 'N' menunjukkan lintang utara<br/>                dan 'S' menunjukkan lintang selatan. |
| GPS_DEST_LONGITUDE | Menunjukkan bujur titik tujuan. Bujur dinyatakan sebagai tiga nilai RATIONAL yang memberikan<br/>                derajat, menit, dan detik, masing-masing. Jika bujur dinyatakan dalam derajat, menit, dan detik, format tipikalnya adalah ddd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua tempat desimal, formatnya menjadi ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Menunjukkan apakah bujur titik tujuan adalah bujur timur atau barat. ASCII 'E' menunjukkan bujur timur,<br/>                dan 'W' menunjukkan bujur barat. |
| GPS_DIFFERENTIAL | Menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS. |
| GPS_IFD_POINTER | Penunjuk gps ifd. |
| GPS_IMG_DIRECTION | Menunjukkan arah gambar saat diambil. Rentang nilai adalah dari 0,00 hingga 359,99. |
| GPS_IMG_DIRECTION_REF | Menunjukkan referensi untuk memberikan arah gambar saat diambil. 'T' menunjukkan arah sejati dan 'M' adalah<br/>                arah magnetik. |
| GPS_LATITUDE | Menunjukkan lintang. Lintang diekspresikan sebagai tiga nilai RATIONAL yang memberikan derajat, menit, dan<br/>                detik, masing-masing. Jika lintang diekspresikan dalam derajat, menit, dan detik, format tipikalnya adalah<br/>                dd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua<br/>                tempat desimal, formatnya adalah dd/1,mmmm/100,0/1. |
| GPS_LATITUDE_REF | Menunjukkan apakah lintang berada di utara atau selatan. |
| GPS_LONGITUDE | Menunjukkan bujur. Bujur diekspresikan sebagai tiga nilai RATIONAL yang memberikan derajat, menit, dan<br/>                detik, masing-masing. Jika bujur diekspresikan dalam derajat, menit, dan detik, format tipikalnya adalah<br/>                ddd/1,mm/1,ss/1. Ketika derajat dan menit digunakan dan, misalnya, pecahan menit diberikan hingga dua<br/>                tempat desimal, formatnya adalah ddd/1,mmmm/100,0/1. |
| GPS_LONGITUDE_REF | Menunjukkan apakah bujur berada di timur atau barat. |
| GPS_MAP_DATUM | Menunjukkan data survei geodetik yang digunakan oleh penerima GPS. |
| GPS_MEASURE_MODE | Menunjukkan mode pengukuran GPS. - 2- atau 3- dimensi. |
| GPS_PROCESSING_METHOD | String karakter yang merekam nama metode yang digunakan untuk menemukan lokasi.<br/>                Byte pertama menunjukkan kode karakter yang digunakan, dan diikuti oleh nama<br/>                metode tersebut. |
| GPS_SATELLITES | Menunjukkan satelit GPS yang digunakan untuk pengukuran. Tag ini dapat digunakan untuk menggambarkan jumlah satelit,<br/>                nomor ID mereka, sudut elevasi, azimut, SNR, dan informasi lain dalam notasi ASCII. Formatnya tidak<br/>                ditentukan. Jika penerima GPS tidak mampu melakukan pengukuran, nilai tag harus diset ke NULL. |
| GPS_SPEED | Menunjukkan kecepatan pergerakan penerima GPS. |
| GPS_SPEED_REF | Menunjukkan satuan yang digunakan untuk menyatakan kecepatan pergerakan penerima GPS. 'K' 'M' dan 'N' mewakili kilometer per<br/>                jam, mil per jam, dan knot. |
| GPS_STATUS | Menunjukkan status penerima GPS saat gambar direkam. |
| GPS_TIMESTAMP | Menunjukkan waktu sebagai UTC (Coordinated Universal Time). TimeStamp dinyatakan sebagai tiga nilai RATIONAL<br/>                yang memberikan jam, menit, dan detik. |
| GPS_TRACK | Menunjukkan arah pergerakan penerima GPS. Rentang nilai adalah dari 0.00 hingga 359.99. |
| GPS_TRACK_REF | Menunjukkan referensi untuk memberikan arah pergerakan penerima GPS. 'T' menunjukkan arah sejati dan 'M' adalah<br/>                arah magnetik. |
| GPS_VERSION_ID | Menunjukkan versi GPSInfoIFD. |
| IMAGE_DESCRIPTION | String karakter yang memberikan judul gambar. Bisa berupa komentar seperti "1988 company picnic" atau sejenisnya. |
| IMAGE_LENGTH | Jumlah baris data gambar. |
| IMAGE_UNIQUE_ID | ID unik gambar. |
| IMAGE_WIDTH | Jumlah kolom data gambar, sama dengan jumlah piksel per baris. |
| ISO_SPEED | Informasi tentang nilai kecepatan iso sebagaimana didefinisikan dalam ISO 12232. |
| ISO_SPEED_LATITUDE_YYY | Tag ini menunjukkan nilai lintang yyy kecepatan ISO sebagaimana didefinisikan dalam ISO 12232. |
| ISO_SPEED_LATITUDE_ZZZ | Tag ini menunjukkan nilai lintang zzz kecepatan ISO sebagaimana didefinisikan dalam ISO 12232. |
| JPEG_INTERCHANGE_FORMAT | Offset ke byte awal (SOI) data thumbnail terkompres JPEG. Ini tidak digunakan untuk data JPEG gambar utama. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | Jumlah byte data thumbnail terkompres JPEG. Ini tidak digunakan untuk data JPEG gambar utama. Thumbnail JPEG tidak dibagi tetapi dicatat sebagai aliran bit JPEG kontinu dari SOI ke EOI. Penanda Appn dan COM tidak boleh dicatat. Thumbnail terkompres harus dicatat tidak lebih dari 64 Kbyte, termasuk semua data lain yang akan dicatat dalam APP1. |
| LENS_MAKE | Tag ini mencatat produsen lensa |
| LENS_MODEL | Tag ini mencatat nama model lensa dan nomor modelnya |
| LENS_SERIAL_NUMBER | Tag ini mencatat nomor seri lensa yang dapat dipertukarkan |
| LENS_SPECIFICATION | Tag ini mencatat panjang fokus minimum, panjang fokus maksimum, angka F minimum pada panjang fokus minimum, dan angka F minimum pada panjang fokus maksimum |
| LIGHT_SOURCE | Jenis sumber cahaya. |
| MAKE | Produsen peralatan perekaman. Ini adalah produsen DSC, pemindai, digitalizer video, atau peralatan lain yang menghasilkan gambar. Jika bidang ini dibiarkan kosong, dianggap tidak diketahui. |
| MAKER_NOTE | Tag untuk produsen penulis Exif agar dapat mencatat informasi apa pun yang diinginkan. Isiannya terserah produsen, tetapi tag ini tidak boleh digunakan untuk tujuan lain selain yang dimaksudkan. |
| MAX_APERTURE_VALUE | Nilai aperture maksimum. |
| METERING_MODE | Mode pengukuran. |
| MODEL | Nama model atau nomor model peralatan. Ini adalah nama atau nomor model DSC, pemindai, digitalizer video, atau peralatan lain yang menghasilkan gambar. Jika bidang ini dibiarkan kosong, dianggap tidak diketahui. |
| OECF | Menunjukkan Fungsi Konversi Opto-Listrik (OECF) yang ditentukan dalam ISO 14524. |
| ORIENTATION | Orientasi gambar yang dilihat dalam istilah baris dan kolom. |
| PHOTOGRAPHIC_SENSITIVITY | Menunjukkan Kecepatan ISO dan Latitude ISO kamera atau perangkat input sebagaimana ditentukan dalam ISO 12232. |
| PHOTOMETRIC_INTERPRETATION | Komposisi piksel. |
| PIXEL_X_DIMENSION | Informasi khusus untuk data terkompresi. Ketika sebuah file terkompresi direkam, lebar yang valid dari gambar yang bermakna harus dicatat dalam tag ini, terlepas apakah ada data padding atau penanda restart. |
| PIXEL_Y_DIMENSION | Informasi khusus untuk data terkompresi. Ketika sebuah file terkompresi direkam, tinggi yang valid dari gambar yang bermakna harus dicatat dalam tag ini. |
| PLANAR_CONFIGURATION | Menunjukkan apakah komponen piksel dicatat dalam format chunky atau planar. Jika bidang ini tidak ada, nilai default TIFF 1 (chunky) diasumsikan. |
| PRIMARY_CHROMATICITIES | Kromatisitas tiga warna utama pada gambar. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag informasi ruang warna ColorSpace. |
| RECOMMENDED_EXPOSURE_INDEX | Menunjukkan indeks eksposur yang direkomendasikan |
| REFERENCE_BLACK_WHITE | Nilai titik hitam referensi dan nilai titik putih referensi<br/>                Tidak ada nilai default yang diberikan dalam TIFF, tetapi nilai di bawah ini diberikan sebagai default di sini.<br/>                Ruang warna dideklarasikan<br/>                dalam tag informasi ruang warna, dengan default<br/>                menjadi nilai yang memberikan karakteristik gambar optimal<br/>                Interoperabilitas kondisi ini |
| RELATED_SOUND_FILE | File suara terkait. |
| RESOLUTION_UNIT | Satuan untuk mengukur XResolution dan YResolution. Satuan yang sama digunakan untuk XResolution dan YResolution. Jika resolusi gambar tidak diketahui, 2 (inci) ditetapkan. |
| ROWS_PER_STRIP | Jumlah baris per strip. Ini adalah jumlah baris dalam gambar pada satu strip ketika gambar dibagi menjadi strip. |
| SAMPLES_PER_PIXEL | Jumlah komponen per piksel. Karena standar ini berlaku untuk gambar RGB dan YCbCr, nilai yang ditetapkan untuk tag ini adalah 3. |
| SATURATION | Tag ini menunjukkan arah pemrosesan saturasi yang diterapkan oleh kamera saat gambar diambil. |
| SCENE_CAPTURE_TYPE | Tag ini menunjukkan jenis adegan yang diambil. Itu juga dapat digunakan untuk mencatat mode di mana gambar diambil. |
| SCENE_TYPE | Menunjukkan jenis adegan. Jika sebuah DSC merekam gambar, nilai tag ini harus selalu diatur ke 1, menandakan bahwa gambar tersebut difoto secara langsung. |
| SENSING_METHOD | Menunjukkan tipe sensor gambar pada kamera atau perangkat input. |
| SENSITIVITY_TYPE | Jenis sensitivitas fotografi |
| SHARPNESS | Tag ini menunjukkan arah pemrosesan ketajaman yang diterapkan oleh kamera saat gambar diambil |
| SHUTTER_SPEED_VALUE | Nilai kecepatan rana. |
| SOFTWARE | Tag ini mencatat nama dan versi perangkat lunak atau firmware dari kamera atau perangkat input gambar yang digunakan untuk menghasilkan gambar. Format detail tidak ditentukan, tetapi disarankan untuk mengikuti contoh yang ditampilkan di bawah ini. Ketika bidang ini dibiarkan kosong, dianggap tidak diketahui. |
| SPATIAL_FREQUENCY_RESPONSE | Tag ini mencatat tabel frekuensi spasial kamera atau perangkat input serta nilai SFR dalam arah lebar gambar, tinggi gambar, dan arah diagonal, sebagaimana ditentukan dalam ISO 12233. |
| SPECTRAL_SENSITIVITY | Menunjukkan sensitivitas spektral setiap saluran kamera yang digunakan. |
| STANDARD_OUTPUT_SENSITIVITY | Menunjukkan sensitivitas output standar kamera |
| STRIP_BYTE_COUNTS | Jumlah total byte dalam setiap strip. |
| STRIP_OFFSETS | Untuk setiap strip, offset byte dari strip tersebut. Disarankan agar ini dipilih sehingga jumlah byte strip tidak melebihi 64 Kbyte.<br/>                Aux tag. |
| SUBJECT_AREA | Tag ini menunjukkan lokasi dan area subjek utama dalam keseluruhan adegan. |
| SUBJECT_DISTANCE | Jarak ke subjek, diberikan dalam meter. |
| SUBJECT_DISTANCE_RANGE | Tag ini menunjukkan jarak ke subjek. |
| SUBJECT_LOCATION | Menunjukkan lokasi subjek utama dalam adegan. Nilai tag ini mewakili piksel di pusat subjek utama relatif terhadap tepi kiri, sebelum pemrosesan rotasi sesuai tag Rotation. |
| SUBSEC_TIME | Tag yang digunakan untuk merekam pecahan detik untuk tag DateTime. |
| SUBSEC_TIME_DIGITIZED | Tag yang digunakan untuk merekam pecahan detik untuk tag DateTimeDigitized. |
| SUBSEC_TIME_ORIGINAL | Tag yang digunakan untuk merekam pecahan detik untuk tag DateTimeOriginal. |
| TRANSFER_FUNCTION | Fungsi transfer untuk gambar, dijelaskan dalam gaya tabel. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag informasi ruang warna ColorSpace. |
| USER_COMMENT | Tag untuk pengguna Exif menulis kata kunci atau komentar pada gambar selain yang ada di ImageDescription, dan tanpa batasan kode karakter pada tag ImageDescription. |
| WHITE_BALANCE | Tag ini menunjukkan mode keseimbangan putih yang diatur saat gambar diambil. |
| WHITE_POINT | Kromatisitas titik putih pada gambar. Biasanya tag ini tidak diperlukan, karena ruang warna ditentukan dalam tag informasi ruang warna ColorSpace. |
| X_RESOLUTION | Jumlah piksel per ResolutionUnit dalam arah ImageWidth. Ketika resolusi gambar tidak diketahui, ditetapkan 72 [dpi]. |
| Y_CB_CR_COEFFICIENTS | Koefisien matriks untuk transformasi dari data gambar RGB ke YCbCr. |
| Y_CB_CR_POSITIONING | Posisi komponen krominansi relatif terhadap komponen<br/>                luminansi. Field ini ditetapkan hanya untuk<br/>                data terkompres JPEG atau data YCbCr tidak terkompres. Default TIFF<br/>                adalah 1 (ditengah); tetapi ketika Y:Cb:Cr = 4:2:2 disarankan dalam standar ini agar 2 (bersebelahan) digunakan untuk<br/>                merekam data, guna meningkatkan kualitas gambar saat dilihat<br/>                pada sistem TV. Ketika field ini tidak ada, pembaca harus<br/>                mengasumsikan default TIFF. Dalam kasus Y:Cb:Cr = 4:2:0, default TIFF (ditengah) disarankan. Jika pembaca<br/>                tidak memiliki kemampuan mendukung kedua jenis<br/>                YCbCrPositioning, ia harus mengikuti default TIFF terlepas<br/>                dari nilai dalam field ini. Lebih disukai agar pembaca "<br/>                dapat mendukung baik posisi ditengah maupun bersebelahan. |
| Y_CB_CR_SUB_SAMPLING | Rasio sampling komponen krominansi relatif terhadap komponen luminansi. |
| Y_RESOLUTION | Jumlah piksel per ResolutionUnit dalam arah ImageLength. Nilai yang sama dengan XResolution ditetapkan. |
