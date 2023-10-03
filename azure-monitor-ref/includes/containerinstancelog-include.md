---
ms.service: azure-monitor
ms.topic: include
ms.date: 08/28/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: ContainerInstanceLog
---


| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| ContainerGroup | string | The name of the container group associated with the record. |
| ContainerID | string | A unique identifier for the container associated with the record. |
| ContainerImage | string | The name of the container image associated with the record. |
| ContainerName | string | The name of the container associated with the record. |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Location | string | The location of the resource associated with the record. |
| Message | string | If applicable, the message from the container. |
| OSType | string | The name of the operating system the container is based on. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| Source | string | Name of the logging component. |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TimeGenerated | datetime | Timestamp when the event was generated by the Azure service processing the request corresponding the event. |
| Type | string | The name of the table |