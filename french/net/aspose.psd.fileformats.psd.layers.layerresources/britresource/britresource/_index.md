---
title: "BritResource.BritResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur BritResource. Initialise une nouvelle instance de la classe BritResource"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/britresource/
---
{{< psd/tize >}}
## BritResource() {#constructor}

Initialise une nouvelle instance de la classe [`BritResource`](../).

```csharp
public BritResource()
```

### Voir aussi

* class [BritResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## BritResource(short, short, short, bool) {#constructor_2}

Initialise une nouvelle instance de la classe [`BritResource`](../).

```csharp
public BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, 
    bool labColor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| luminosité | Int16 | La luminosité. |
| contraste | Int16 | Le contraste. |
| meanValueForBrightnessAndContrast | Int16 | La valeur moyenne pour la luminosité et le contraste. |
| labColor | Booléen | si défini sur `true` [lab color]. |

### Voir aussi

* class [BritResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## BritResource(byte[]) {#constructor_1}

Initialise une nouvelle instance de la classe [`BritResource`](../). La spécification du format PSD contient la description suivante : 2 Luminosité 2 Contraste 2 Valeur moyenne pour la luminosité et le contraste 1 uniquement couleur Lab. Elle n'est pas utilisée dans les PSD modernes (CS5 et plus) où CgEd est présent. CgEd stocke les propriétés d'information.

```csharp
public BritResource(byte[] bytes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| octets | Byte[] | Les octets. |

### Voir aussi

* class [BritResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


