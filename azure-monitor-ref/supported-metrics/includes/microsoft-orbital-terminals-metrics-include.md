---
ms.service: azure-monitor
ms.topic: include
ms.date: 01/10/2024
ms.author: edbaynash
author: EdB-MSFT
ms.custom: Microsoft.Orbital/terminals, naam

# NOTE:  This content is automatically generated using API calls to Azure. Any edits made on these files will be overwritten in the next run of the script. 
 
---

  
  
|Category|Metric|Name in REST API|Unit|Aggregation|Dimensions|Time Grains|DS Export|
|---|---|---|---|---|---|---|---|
|Error|**SDWAN alarms**<p><p>SDWAN alarms |`JuniperAlarm` |Count |Total, Count |`category`, `id`, `message`, `node`, `number`, `process`, `router`, `severity`, `shelvedReason`, `source`, `time`|PT1M |Yes|
|Traffic|**Satcom SDWAN bandwidth**<p><p>Satcom SDWAN bandwidth in bytes per second |`JuniperSsrBandwidthBytesPerSecond` |BytesPerSecond |Average |\<none\>|PT1M |Yes|
|Traffic|**Satcom SDWAN bytes**<p><p>Satcom SDWAN total bytes |`JuniperSsrBytes` |Bytes |Average |\<none\>|PT1M |Yes|
|Traffic|**Satcom SDWAN packet loss**<p><p>Satcom SDWAN total packets lost |`JuniperSsrPacketLoss` |Count |Average |\<none\>|PT1M |Yes|
|Traffic|**Satcom VPN gateway incoming bytes**<p><p>Satcom VPN gateway total incoming bytes |`TunnelIncomingTotalBytes` |Bytes |Average |\<none\>|PT1M |Yes|
|Traffic|**Satcom VPN gateway outgoing bytes**<p><p>Satcom VPN gateway total outgoing bytes |`TunnelOutgoingTotalBytes` |Bytes |Average |\<none\>|PT1M |Yes|
|Traffic|**Satcom VPN gateway bandwidth**<p><p>Satcom VPN gateway bandwidth in bytes per second |`TunnelTotalBandwidthBytesPerSecond` |BytesPerSecond |Average |\<none\>|PT1M |Yes|