---
ms.service: azure-monitor
ms.topic: include
ms.date: 08/28/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: WindowsServerAssessmentRecommendation
---


| Column | Type | Description |
|---|---|---|
| ActionArea | string |   |
| ActionAreaId | string |   |
| AffectedObjectName | string |   |
| AffectedObjectType | string |   |
| AssessmentId | string |   |
| _BilledSize | real | The record size in bytes |
| Cluster | string |   |
| Computer | string |   |
| CustomData | string |   |
| Description | string |   |
| Domain | string |   |
| FocusArea | string |   |
| FocusAreaId | string |   |
| HyperVMHost | string |   |
| IISApplication | string |   |
| IISApplicationPool | string |   |
| Ipv4Address | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OSVersion | string |   |
| Recommendation | string |   |
| RecommendationId | string |   |
| RecommendationResult | string |   |
| RecommendationWeight | real |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| Server | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| Technology | string |   |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
| WebServer | string |   |
| WebSite | string |   |
