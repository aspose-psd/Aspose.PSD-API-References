---
title: "فئة مقيسة"
type: docs
weight: 3030
url: /ar/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Metered()](#Metered__1) | ينشئ مثيلاً جديدًا من الفئة المقيسة |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | يحصل على رصيد الاستهلاك |
| [get_consumption_quantity()](#get_consumption_quantity__2) | يحصل على حجم ملف الاستهلاك |
| [get_product_name()](#get_product_name__3) | يحصل على اسم المنتج. |
| [is_metered_licensed()](#is_metered_licensed__4) | تحقق مما إذا كانت المقيسة مرخصة |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | يضبط المفتاح العام والخاص للمقيسة.<br/>            إذا قمت بشراء ترخيص مقيس، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً هذا يكفي. <br/>            ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم ضبط الترخيص إلى حالة التقييم، <br/>            لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

ينشئ مثيلاً جديدًا من الفئة المقيسة

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

يحصل على رصيد الاستهلاك

**Returns**

| النوع | الوصف |
| :- | :- |
| عشري | كمية الاستهلاك |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

يحصل على حجم ملف الاستهلاك

**Returns**

| النوع | الوصف |
| :- | :- |
| عشري | كمية الاستهلاك |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

يحصل على اسم المنتج.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | اسم المنتج المرخص |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

تحقق مما إذا كانت المقيسة مرخصة

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | صحيح أو خطأ |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

يضبط المفتاح العام والخاص للمقيسة.<br/>            إذا قمت بشراء ترخيص مقيس، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً هذا يكفي. <br/>            ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم ضبط الترخيص إلى حالة التقييم، <br/>            لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| public_key | string | المفتاح العام |
| private_key | string | المفتاح الخاص |

