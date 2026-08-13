---
title: "Classe Metered"
type: docs
weight: 3030
url: /fr/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Metered()](#Metered__1) | Initialise une nouvelle instance de la classe Metered |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Obtient le crédit de consommation |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Obtient la taille du fichier de consommation |
| [get_product_name()](#get_product_name__3) | Obtient le nom du produit. |
| [is_metered_licensed()](#is_metered_licensed__4) | Vérifie si Metered est licencié |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Définit les clés publiques et privées de Metered.<br/>            Si vous achetez une licence Metered, au démarrage de l'application, cette API doit être appelée, normalement, cela suffit. <br/>            Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation, <br/>            pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, si elle est en statut d'évaluation, appelez à nouveau cette API. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initialise une nouvelle instance de la classe Metered

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Obtient le crédit de consommation

**Returns**

| Type | Description |
| :- | :- |
| décimal | quantité de consommation |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Obtient la taille du fichier de consommation

**Returns**

| Type | Description |
| :- | :- |
| décimal | quantité de consommation |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Obtient le nom du produit.

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Nom du produit licencié |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Vérifie si Metered est licencié

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai ou faux |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Définit les clés publiques et privées de Metered.<br/>            Si vous achetez une licence Metered, au démarrage de l'application, cette API doit être appelée, normalement, cela suffit. <br/>            Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation, <br/>            pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, si elle est en statut d'évaluation, appelez à nouveau cette API.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| public_key | chaîne | clé publique |
| private_key | chaîne | clé privée |

