---
title: "Kelas PsdLoadOptions"
type: docs
weight: 30
url: /id/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Menginisialisasi instance baru dari kelas PsdLoadOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Mendapatkan atau mengatur apakah menyimpan dengan gambar yang dirender, dengan atau tanpa transformasi warp. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur [Image](/psd/python-net/aspose.psd/image/) latar belakang [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Mendapatkan atau mengatur mode pemulihan data. |
| ignore_alpha_channel | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar tetap lapisan teks PSD akan diabaikan pada pelaksanaan operasi UpdateText. |
| load_effects_resource | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [load effects resource] (secara default sumber daya tidak dimuat). Ketika opsi ini diatur, hanya efek yang didukung yang akan dirender ke gambar gabungan akhir. |
| read_only_mode | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use read only mode]. Ini adalah mode hanya-baca, didukung untuk kompatibilitas identik dengan Adobe Photoshop.<br/>            Ketika opsi ini diatur, semua perubahan yang diterapkan pada lapisan tidak akan disimpan ke gambar akhir. Semua data diambil dari bagian ImageData, sehingga identik dengan Photoshop. <br/>            Secara default semua gambar yang dimuat tidak kompatibel secara identik dengan Adobe Photoshop. |
| use_disk_for_load_effects_resource | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use disk for load effects resource] (secara default menggunakan disk untuk memuat sumber daya efek, tetapi dapat menggunakan memori jika cukup dengan mengatur nilai ini menjadi false). |
| use_icc_profile_conversion | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah konversi profil ICC harus diterapkan. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Menginisialisasi instance baru dari kelas PsdLoadOptions

