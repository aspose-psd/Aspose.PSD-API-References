---
title: "Classe Metered"
type: docs
weight: 3030
url: /it/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Metered()](#Metered__1) | Inizializza una nuova istanza della classe Metered |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Ottiene il credito di consumo |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Ottiene la dimensione del file di consumo |
| [get_product_name()](#get_product_name__3) | Ottiene il nome del prodotto. |
| [is_metered_licensed()](#is_metered_licensed__4) | Verifica se Metered è licenziato |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Imposta la chiave pubblica e privata di Metered.<br/>            Se acquisti una licenza Metered, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente. <br/>            Tuttavia, se fallisci sempre nel caricare i dati di consumo e superi le 24 ore, la licenza verrà impostata allo stato di valutazione, <br/>            per evitare tale caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Inizializza una nuova istanza della classe Metered

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Ottiene il credito di consumo

**Returns**

| Tipo | Descrizione |
| :- | :- |
| decimale | quantità di consumo |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Ottiene la dimensione del file di consumo

**Returns**

| Tipo | Descrizione |
| :- | :- |
| decimale | quantità di consumo |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Ottiene il nome del prodotto.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Nome del prodotto con licenza |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Verifica se Metered è licenziato

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero o falso |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Imposta la chiave pubblica e privata di Metered.<br/>            Se acquisti una licenza Metered, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente. <br/>            Tuttavia, se fallisci sempre nel caricare i dati di consumo e superi le 24 ore, la licenza verrà impostata allo stato di valutazione, <br/>            per evitare tale caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| public_key | string | chiave pubblica |
| private_key | string | chiave privata |

