---
ms.service: azure-monitor
ms.topic: include
ms.date: 08/28/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: ServiceFabricOperationalEvent
---


| Column | Type | Description |
|---|---|---|
| ApplicationName | string |   |
| ApplicationTypeName | string |   |
| ApplicationTypeVersion | string |   |
| AzureDeploymentID | string |   |
| _BilledSize | real | The record size in bytes |
| ChannelName | string |   |
| Computer | string |   |
| EventId | int |   |
| EventMessage | string |   |
| EventSourceName | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| KeywordName | string |   |
| Level | string |   |
| OpcodeName | string |   |
| PartitionId | string |   |
| Pid | int |   |
| ProviderGuid | string |   |
| Role | string |   |
| ServiceName | string |   |
| ServiceTypeName | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| TaskName | string |   |
| Tid | int |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
| UpgradeDomains | string |   |
