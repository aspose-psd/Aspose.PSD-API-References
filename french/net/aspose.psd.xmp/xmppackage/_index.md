---
title: Class XmpPackage
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Xmp.XmpPackage classe. Définit la classe XmpPackage qui représente labstraction de base pour le package XMP.
type: docs
weight: 6270
url: /fr/net/aspose.psd.xmp/xmppackage/
---
## XmpPackage class

Définit la classe XmpPackage qui représente l'abstraction de base pour le package XMP.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Obtient ou définit leObject avec la clé spécifiée. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | Obtient les clés dans le package XMP. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Obtient l'URI de l'espace de noms. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Obtient le préfixe. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | Obtient l'espace de noms XML. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Ajoute la valeur. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Efface cette instance. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Détermine si la clé spécifiée contient key. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Renvoie un énumérateur qui parcourt la collection. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | Convertit la valeur XMP en représentation XML. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Supprimer la valeur avec la clé spécifiée. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Définit la valeur. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Définit la valeur du type XMP. |

### Voir également

* interface [IXmlValue](../ixmlvalue/)
* espace de noms [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* Assemblée [Aspose.PSD](../../)


