---
title: "Класс Metered"
type: docs
weight: 3030
url: /ru/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Metered()](#Metered__1) | Инициализирует новый экземпляр класса Metered |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Получает кредит потребления |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Получает размер файла потребления |
| [get_product_name()](#get_product_name__3) | Получает название продукта. |
| [is_metered_licensed()](#is_metered_licensed__4) | Проверьте, лицензирован ли Metered |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Устанавливает публичный и приватный ключ Metered.<br/>            Если вы покупаете лицензию Metered, при запуске приложения этот API должен быть вызван, обычно этого достаточно. <br/>            Однако, если постоянно не удаётся загрузить данные потребления и прошло более 24 часов, лицензия будет переведена в статус оценки, <br/>            чтобы избежать такой ситуации, следует регулярно проверять статус лицензии; если он находится в статусе оценки, вызовите этот API снова. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Инициализирует новый экземпляр класса Metered

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Получает кредит потребления

**Returns**

| Тип | Описание |
| :- | :- |
| десятичный | количество потребления |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Получает размер файла потребления

**Returns**

| Тип | Описание |
| :- | :- |
| десятичный | количество потребления |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Получает название продукта.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Название лицензированного продукта |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Проверьте, лицензирован ли Metered

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Истина или ложь |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Устанавливает публичный и приватный ключ Metered.<br/>            Если вы покупаете лицензию Metered, при запуске приложения этот API должен быть вызван, обычно этого достаточно. <br/>            Однако, если постоянно не удаётся загрузить данные потребления и прошло более 24 часов, лицензия будет переведена в статус оценки, <br/>            чтобы избежать такой ситуации, следует регулярно проверять статус лицензии; если он находится в статусе оценки, вызовите этот API снова.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| public_key | string | публичный ключ |
| private_key | string | приватный ключ |

