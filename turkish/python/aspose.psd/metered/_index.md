---
title: "Ölçülen Sınıf"
type: docs
weight: 3030
url: /tr/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Metered()](#Metered__1) | Metered sınıfının yeni bir örneğini başlatır |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Tüketim kredisini alır |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Tüketim dosya boyutunu alır |
| [get_product_name()](#get_product_name__3) | Ürünün adını alır. |
| [is_metered_licensed()](#is_metered_licensed__4) | Metered'in lisanslı olup olmadığını kontrol et |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Metered genel ve özel anahtarı ayarlar.<br/>            Metered lisansı satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. <br/>            Ancak, tüketim verilerini yüklemekte sürekli başarısız olur ve 24 saati aşarsa, lisans değerlendirme durumuna ayarlanır, <br/>            bu durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa, bu API'yi tekrar çağırın. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Metered sınıfının yeni bir örneğini başlatır

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Tüketim kredisini alır

**Returns**

| Tür | Açıklama |
| :- | :- |
| ondalık | tüketim miktarı |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Tüketim dosya boyutunu alır

**Returns**

| Tür | Açıklama |
| :- | :- |
| ondalık | tüketim miktarı |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Ürünün adını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Lisanslı ürünün adı |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Metered'in lisanslı olup olmadığını kontrol et

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Doğru ya da yanlış |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Metered genel ve özel anahtarı ayarlar.<br/>            Metered lisansı satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. <br/>            Ancak, tüketim verilerini yüklemekte sürekli başarısız olur ve 24 saati aşarsa, lisans değerlendirme durumuna ayarlanır, <br/>            bu durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa, bu API'yi tekrar çağırın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| public_key | string | genel anahtar |
| private_key | string | özel anahtar |

