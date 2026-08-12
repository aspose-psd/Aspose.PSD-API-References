---
title: "Clase XmpPacketWrapper"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Xmp.XmpPacketWrapper. Contiene el paquete xmp serializado, incluyendo encabezado y tráiler"
type: docs
weight: 6790
url: /es/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Contiene el paquete xmp serializado, incluyendo encabezado y trailer.

```csharp
public class XmpPacketWrapper
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Inicializa una nueva instancia de la clase `XmpPacketWrapper`. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Inicializa una nueva instancia de la clase `XmpPacketWrapper`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Obtiene la instrucción de procesamiento del encabezado. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Obtiene los metadatos XMP. Opcional. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Obtiene una matriz de [`XmpPackage`](../xmppackage/) dentro de XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Obtiene la cantidad de paquetes dentro de la estructura XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Obtiene la instrucción de procesamiento del tráiler. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Añade el paquete. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Elimina todos los [`XmpPackage`](../xmppackage/) dentro de XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Determina si el paquete existe en el contenedor xmp. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Obtiene el paquete por URI de espacio de nombres. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Elimina el paquete XMP. |

## Observaciones

Un contenedor que consiste en un par de instrucciones de procesamiento XML (PIs) puede colocarse alrededor del elemento rdf:RDF.

### Ver también

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


