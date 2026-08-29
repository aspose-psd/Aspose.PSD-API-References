---
title: "Clase XmpPackage"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Xmp.XmpPackage. Define la clase XmpPackage que representa la abstracción base para el paquete XMP."
type: docs
weight: 6770
url: /es/net/aspose.psd.xmp/xmppackage/
---
{{< psd/tize >}}
## XmpPackage class

Define la clase XmpPackage que representa la abstracción base para el paquete XMP.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Obtiene o establece el objeto con la clave especificada. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | Obtiene las claves del paquete XMP. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Obtiene el URI del espacio de nombres. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Obtiene el prefijo. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | Obtiene el espacio de nombres XML. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Agrega el valor. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Limpia esta instancia. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Determina si la clave especificada contiene la clave. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Devuelve un enumerador que recorre la colección. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | Convierte el valor XMP a la representación XML. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Elimina el valor con la clave especificada. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Establece el valor. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Establece el valor del tipo XMP. |

### Ver también

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


