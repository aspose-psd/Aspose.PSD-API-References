---
title: SplitStreamContainer.Read
second_title: Referencia de API de Aspose.PSD para .NET
description: SplitStreamContainer método. Lee bytes para llenar el búfer de bytes especificado.
type: docs
weight: 110
url: /es/net/aspose.psd/splitstreamcontainer/read/
---
## Read(byte[]) {#read}

Lee bytes para llenar el búfer de bytes especificado.

```csharp
public override int Read(byte[] bytes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| bytes | Byte[] | Los bytes a llenar. |

### Valor_devuelto

El número de bytes leídos. Este valor puede ser menor que el número de bytes en el búfer si no hay suficientes bytes en la transmisión.

### Ver también

* class [SplitStreamContainer](../)
* espacio de nombres [Aspose.PSD](../../splitstreamcontainer/)
* asamblea [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo según el número de bytes leídos.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| buffer | Byte[] | Una matriz de bytes. Cuando este método regresa, el búfer contiene la matriz de bytes especificada con los valores entre*offset* y (*offset* +*count* - 1) reemplazado por los bytes leídos de la fuente actual. |
| offset | Int32 | El desplazamiento de bytes de base cero en*buffer* en el que comenzar a almacenar los datos leídos del flujo actual. |
| count | Int32 | El número máximo de bytes que se leerán del flujo actual. |

### Valor_devuelto

El número total de bytes leídos en el búfer. Puede ser menor que la cantidad de bytes solicitados si esa cantidad de bytes no está disponible actualmente, o cero (0) si se alcanzó el final de la secuencia.

### Ver también

* class [SplitStreamContainer](../)
* espacio de nombres [Aspose.PSD](../../splitstreamcontainer/)
* asamblea [Aspose.PSD](../../../)


