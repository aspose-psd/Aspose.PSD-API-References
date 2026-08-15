---
title: "Måttklass"
type: docs
weight: 3030
url: /sv/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Metered()](#Metered__1) | Initierar en ny instans av Metered-klassen |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Hämtar förbrukningskredit |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Hämtar förbrukningsfilens storlek |
| [get_product_name()](#get_product_name__3) | Hämtar namnet på produkten. |
| [is_metered_licensed()](#is_metered_licensed__4) | Kontrollera om metered är licensierad |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Sätter metered offentliga och privata nyckel.<br/>            Om du köper en metered-licens, när du startar applikationen bör detta API anropas, normalt räcker detta. <br/>            Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus, <br/>            för att undvika detta bör du regelbundet kontrollera licensstatusen, om den är i utvärderingsstatus, anropa detta API igen. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initierar en ny instans av Metered-klassen

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Hämtar förbrukningskredit

**Returns**

| Typ | Beskrivning |
| :- | :- |
| decimal | förbrukningskvantitet |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Hämtar förbrukningsfilens storlek

**Returns**

| Typ | Beskrivning |
| :- | :- |
| decimal | förbrukningskvantitet |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Hämtar namnet på produkten.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Namn på licensierad produkt |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Kontrollera om metered är licensierad

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant eller falskt |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Sätter metered offentliga och privata nyckel.<br/>            Om du köper en metered-licens, när du startar applikationen bör detta API anropas, normalt räcker detta. <br/>            Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus, <br/>            för att undvika detta bör du regelbundet kontrollera licensstatusen, om den är i utvärderingsstatus, anropa detta API igen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| public_key | string | offentlig nyckel |
| private_key | string | privat nyckel |

