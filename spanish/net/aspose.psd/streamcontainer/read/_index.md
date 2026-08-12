---
title: "StreamContainer.Read"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método StreamContainer. Lee bytes para llenar el búfer de bytes especificado"
type: docs
weight: 110
url: /es/net/aspose.psd/streamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

Lee bytes para llenar el búfer de bytes especificado.

```csharp
public virtual int Read(byte[] bytes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | Byte[] | Los bytes a llenar. |

### Valor devuelto

El número de bytes leídos. Este valor puede ser menor que el número de bytes en el búfer si no hay suficientes bytes en el stream.

### Ver también

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos.

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | Byte[] | Una matriz de bytes. Cuando este método retorna, el búfer contiene la matriz de bytes especificada con los valores entre *offset* y (*offset* + *count* - 1) reemplazados por los bytes leídos de la fuente actual. |
| desplazamiento | Int32 | El desplazamiento de bytes basado en cero en *buffer* en el que comenzar a almacenar los datos leídos del stream actual. |
| count | Int32 | El número máximo de bytes que se leerán del stream actual. |

### Valor devuelto

El número total de bytes leídos en el búfer. Esto puede ser menor que el número de bytes solicitados si esa cantidad de bytes no está disponible actualmente, o cero (0) si se ha alcanzado el final del stream.

### Ver también

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


