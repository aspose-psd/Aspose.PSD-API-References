---
title: "Enum DataRecoveryMode"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.DataRecoveryMode-enum. Dataåterställningsläget."
type: docs
weight: 740
url: /sv/net/aspose.psd/datarecoverymode/
---
{{< psd/tize >}}
## DataRecoveryMode enumeration

Datåterställningsläget.

```csharp
public enum DataRecoveryMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Ingen dataåterställning antas. När filformatet har korrupt data kastas lämpligt undantag. |
| ConsistentRecover | `1` | Det konsekventa återställningsläget försöker återställa all data så länge korruptionen inte bryter filformatet och möjliggör korrekt vidare bearbetning. |
| MaximalRecover | `2` | Det maximala återställningsläget återställer all data även om filformatet har en korrupt struktur och vidare bearbetning kan leda till oönskade effekter. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


