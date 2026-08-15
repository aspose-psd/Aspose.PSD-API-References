---
title: "Metered Klasse"
type: docs
weight: 3030
url: /nl/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Metered()](#Metered__1) | Initialiseert een nieuw exemplaar van de Metered klasse |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Haalt verbruikskrediet op |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Haalt de bestandsgrootte van het verbruik op |
| [get_product_name()](#get_product_name__3) | Haalt de naam van het product op. |
| [is_metered_licensed()](#is_metered_licensed__4) | Controleer of Metered gelicentieerd is |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Stelt de openbare en privé‑sleutel van Metered in.<br/>            Als u een Metered‑licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen; normaal gesproken is dit voldoende. <br/>            Als het echter steeds mislukt om verbruiksgegevens te uploaden en de 24 uur overschrijdt, wordt de licentie op evaluatiestatus gezet, <br/>            om zo’n geval te voorkomen, moet u regelmatig de licentiestatus controleren; als deze evaluatiestatus is, roep dan deze API opnieuw aan. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initialiseert een nieuw exemplaar van de Metered klasse

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Haalt verbruikskrediet op

**Returns**

| Type | Beschrijving |
| :- | :- |
| decimaal | verbruikshoeveelheid |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Haalt de bestandsgrootte van het verbruik op

**Returns**

| Type | Beschrijving |
| :- | :- |
| decimaal | verbruikshoeveelheid |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Haalt de naam van het product op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Naam van gelicentieerd product |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Controleer of Metered gelicentieerd is

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Waar of onwaar |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Stelt de openbare en privé‑sleutel van Metered in.<br/>            Als u een Metered‑licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen; normaal gesproken is dit voldoende. <br/>            Als het echter steeds mislukt om verbruiksgegevens te uploaden en de 24 uur overschrijdt, wordt de licentie op evaluatiestatus gezet, <br/>            om zo’n geval te voorkomen, moet u regelmatig de licentiestatus controleren; als deze evaluatiestatus is, roep dan deze API opnieuw aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| public_key | string | openbare sleutel |
| private_key | string | privé‑sleutel |

