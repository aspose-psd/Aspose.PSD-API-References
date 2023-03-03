---
title: Enum DataRecoveryMode
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.DataRecoveryMode enumeración. El modo de recuperación de datos.
type: docs
weight: 730
url: /es/net/aspose.psd/datarecoverymode/
---
## DataRecoveryMode enumeration

El modo de recuperación de datos.

```csharp
public enum DataRecoveryMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | No se implica la recuperación de datos. Cada vez que el formato de archivo tiene algunos datos corruptos, se lanza la excepción correspondiente. |
| ConsistentRecover | `1` | El modo de recuperación coherente intenta recuperar todos los datos siempre que la corrupción no rompa el formato del archivo y permita un procesamiento posterior correcto. |
| MaximalRecover | `2` | El modo de recuperación máxima recupera todos los datos incluso si el formato del archivo tiene una estructura dañada y el procesamiento posterior puede producir efectos desatendidos. |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


