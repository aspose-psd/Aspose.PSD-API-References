---
title: "SplitStreamContainer.Read"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode SplitStreamContainer. Lit des octets pour remplir le tampon d'octets spécifié."
type: docs
weight: 110
url: /fr/net/aspose.psd/splitstreamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

Lit des octets pour remplir le tampon d'octets spécifié.

```csharp
public override int Read(byte[] bytes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| octets | Byte[] | Les octets à remplir. |

### Valeur de retour

Le nombre d'octets lus. Cette valeur peut être inférieure au nombre d'octets du tampon s'il n'y a pas assez d'octets dans le flux.

### Voir aussi

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Lit une séquence d'octets depuis le flux actuel et avance la position dans le flux du nombre d'octets lus.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| tampon | Byte[] | Un tableau d'octets. Lorsque cette méthode retourne, le tampon contient le tableau d'octets spécifié avec les valeurs entre *offset* et (*offset* + *count* - 1) remplacées par les octets lus depuis la source actuelle. |
| offset | Int32 | Le décalage d'octet basé sur zéro dans *buffer* à partir duquel commencer à stocker les données lues depuis le flux actuel. |
| count | Int32 | Le nombre maximal d'octets à lire depuis le flux actuel. |

### Valeur de retour

Le nombre total d'octets lus dans le tampon. Cela peut être inférieur au nombre d'octets demandé si autant d'octets ne sont pas disponibles actuellement, ou zéro (0) si la fin du flux a été atteinte.

### Voir aussi

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


