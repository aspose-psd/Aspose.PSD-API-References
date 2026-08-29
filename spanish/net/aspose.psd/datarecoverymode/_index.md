---
title: "Enumeración DataRecoveryMode"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Enumeración Aspose.PSD.DataRecoveryMode. El modo de recuperación de datos"
type: docs
weight: 740
url: /es/net/aspose.psd/datarecoverymode/
---
{{< psd/tize >}}
## DataRecoveryMode enumeration

El modo de recuperación de datos.

```csharp
public enum DataRecoveryMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | No se implica recuperación de datos. Cada vez que el formato de archivo tiene datos corruptos, se lanza la excepción correspondiente. |
| ConsistentRecover | `1` | El modo de recuperación consistente intenta recuperar todos los datos siempre que la corrupción no rompa el formato del archivo y permite un procesamiento posterior correcto. |
| MaximalRecover | `2` | El modo de recuperación máximo recupera todos los datos incluso si el formato del archivo tiene una estructura corrupta y el procesamiento posterior puede producir efectos no deseados. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


