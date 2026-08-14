---
title: "Metered-Klasse"
type: docs
weight: 3030
url: /de/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Metered()](#Metered__1) | Initialisiert eine neue Instanz der Metered-Klasse |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Ermittelt Verbrauchsguthaben |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Ermittelt Verbrauchsdateigröße |
| [get_product_name()](#get_product_name__3) | Ermittelt den Namen des Produkts. |
| [is_metered_licensed()](#is_metered_licensed__4) | Prüft, ob Metered lizenziert ist |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Setzt den öffentlichen und privaten Schlüssel von Metered.<br/>            Wenn Sie eine Metered-Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. <br/>            Wenn jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt, <br/>            um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initialisiert eine neue Instanz der Metered-Klasse

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Ermittelt Verbrauchsguthaben

**Returns**

| Typ | Beschreibung |
| :- | :- |
| Dezimal | Verbrauchsmenge |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Ermittelt Verbrauchsdateigröße

**Returns**

| Typ | Beschreibung |
| :- | :- |
| Dezimal | Verbrauchsmenge |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Ermittelt den Namen des Produkts.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Name des lizenzierten Produkts |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Prüft, ob Metered lizenziert ist

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Wahr oder falsch |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Setzt den öffentlichen und privaten Schlüssel von Metered.<br/>            Wenn Sie eine Metered-Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. <br/>            Wenn jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt, <br/>            um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| public_key | string | öffentlicher Schlüssel |
| private_key | string | Privater Schlüssel |

