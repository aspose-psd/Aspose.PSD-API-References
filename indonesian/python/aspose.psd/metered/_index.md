---
title: "Kelas Metered"
type: docs
weight: 3030
url: /id/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Metered()](#Metered__1) | Menginisialisasi instance baru dari kelas Metered |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Mendapatkan kredit konsumsi |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Mendapatkan ukuran file konsumsi |
| [get_product_name()](#get_product_name__3) | Mendapatkan nama produk. |
| [is_metered_licensed()](#is_metered_licensed__4) | Periksa apakah Metered berlisensi |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Menetapkan kunci publik dan pribadi Metered.<br/>            Jika Anda membeli lisensi Metered, saat memulai aplikasi, API ini harus dipanggil, biasanya, ini sudah cukup. <br/>            Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diatur ke status evaluasi, <br/>            untuk menghindari kasus tersebut, Anda harus secara teratur memeriksa status lisensi, jika berada dalam status evaluasi, panggil API ini lagi. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Menginisialisasi instance baru dari kelas Metered

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Mendapatkan kredit konsumsi

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| desimal | jumlah konsumsi |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Mendapatkan ukuran file konsumsi

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| desimal | jumlah konsumsi |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Mendapatkan nama produk.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Nama produk berlisensi |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Periksa apakah Metered berlisensi

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Benar atau salah |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Menetapkan kunci publik dan pribadi Metered.<br/>            Jika Anda membeli lisensi Metered, saat memulai aplikasi, API ini harus dipanggil, biasanya, ini sudah cukup. <br/>            Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diatur ke status evaluasi, <br/>            untuk menghindari kasus tersebut, Anda harus secara teratur memeriksa status lisensi, jika berada dalam status evaluasi, panggil API ini lagi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| public_key | string | kunci publik |
| private_key | string | kunci pribadi |

