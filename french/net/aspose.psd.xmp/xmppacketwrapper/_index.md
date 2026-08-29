---
title: "Classe XmpPacketWrapper"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Xmp.XmpPacketWrapper. Contient le paquet XMP sérialisé incluant l’en-tête et le pied de page"
type: docs
weight: 6790
url: /fr/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Contient le paquet xmp sérialisé incluant l'en-tête et le pied de page.

```csharp
public class XmpPacketWrapper
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Initialise une nouvelle instance de la classe `XmpPacketWrapper`. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Initialise une nouvelle instance de la classe `XmpPacketWrapper`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Obtient l’instruction de traitement de l’en-tête. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Obtient les métadonnées XMP. Facultatif. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Obtient le tableau de [`XmpPackage`](../xmppackage/) à l’intérieur du XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Obtient le nombre de paquets dans la structure XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Obtient l’instruction de traitement du pied de page. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Ajoute le paquet. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Supprime tous les [`XmpPackage`](../xmppackage/) à l’intérieur du XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Détermine si le paquet existe dans le wrapper XMP. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Obtient le paquet par URI d’espace de noms. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Supprime le paquet XMP. |

## Remarques

Un wrapper composé d’une paire d’instructions de traitement XML (PI) peut être placé autour de l’élément rdf:RDF.

### Voir aussi

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


