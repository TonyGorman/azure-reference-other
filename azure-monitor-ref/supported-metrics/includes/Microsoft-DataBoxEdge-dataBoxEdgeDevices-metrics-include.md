---
ms.service: azure-monitor
ms.topic: include
ms.date: 09/19/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: Microsoft.DataBoxEdge/dataBoxEdgeDevices, arm
---
  
  
|Metric|Name|Unit|Aggregation|Dimensions|Time Grains|DS Export|
|---|---|---|---|---|---|---|
|Available Capacity<p><p>The available capacity in bytes during the reporting period. |`AvailableCapacity` |Bytes |Average, Minimum, Maximum |No Dimensions|PT5M, PT15M, PT1H |Yes|
|Cloud Bytes Uploaded (Device)<p><p>The total number of bytes that is uploaded to Azure from a device during the reporting period. |`BytesUploadedToCloud` |Bytes |Average, Minimum, Maximum |No Dimensions|PT5M, PT15M, PT1H |Yes|
|Cloud Bytes Uploaded (Share)<p><p>The total number of bytes that is uploaded to Azure from a share during the reporting period. |`BytesUploadedToCloudPerShare` |Bytes |Average, Minimum, Maximum |Share|PT1M, PT15M, PT1H |Yes|
|Cloud Download Throughput<p><p>The cloud download throughput to Azure during the reporting period. |`CloudReadThroughput` |BytesPerSecond |Average, Minimum, Maximum |No Dimensions|PT5M, PT15M, PT1H |Yes|
|Cloud Download Throughput (Share)<p><p>The download throughput to Azure from a share during the reporting period. |`CloudReadThroughputPerShare` |BytesPerSecond |Average, Minimum, Maximum |Share|PT1M, PT15M, PT1H |Yes|
|Cloud Upload Throughput<p><p>The cloud upload throughput  to Azure during the reporting period. |`CloudUploadThroughput` |BytesPerSecond |Average, Minimum, Maximum |No Dimensions|PT5M, PT15M, PT1H |Yes|
|Cloud Upload Throughput (Share)<p><p>The upload throughput to Azure from a share during the reporting period. |`CloudUploadThroughputPerShare` |BytesPerSecond |Average, Minimum, Maximum |Share|PT1M, PT15M, PT1H |Yes|
|Edge Compute - Memory Usage<p><p>Amount of RAM in Use |`HyperVMemoryUtilization` |Percent |Average, Minimum, Maximum |InstanceName|PT1M, PT15M, PT1H |Yes|
|Edge Compute - Percentage CPU<p><p>Percent CPU Usage |`HyperVVirtualProcessorUtilization` |Percent |Average, Minimum, Maximum |InstanceName|PT1M, PT15M, PT1H |Yes|
|Read Throughput (Network)<p><p>The read throughput of the network interface on the device in the reporting period for all volumes in the gateway. |`NICReadThroughput` |BytesPerSecond |Average, Minimum, Maximum |InstanceName|PT1M, PT15M, PT1H |Yes|
|Write Throughput (Network)<p><p>The write throughput of the network interface on the device in the reporting period for all volumes in the gateway. |`NICWriteThroughput` |BytesPerSecond |Average, Minimum, Maximum |InstanceName|PT1M, PT15M, PT1H |Yes|
|Total Capacity<p><p>The total capacity of the device in bytes during the reporting period. |`TotalCapacity` |Bytes |Average, Minimum, Maximum |No Dimensions|PT5M, PT15M, PT1H |Yes|