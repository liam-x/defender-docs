---
title: Stream Microsoft Defender XDR events
description: Learn how to configure Microsoft Defender XDR to stream Advanced Hunting events to Event Hubs or Azure storage account
keywords: raw data export, streaming API, API, Event hubs, Azure storage, storage account, Advanced Hunting, raw data sharing
search.appverid: met150
ms.service: defender-xdr
ms.author: macapara
author: mjcaparas
ms.localizationpriority: medium
manager: dansimp
audience: ITPro
ms.collection: 
- m365-security
- tier3
ms.topic: conceptual
ms.date: 07/25/2023
---

# Streaming API

[!INCLUDE [Microsoft Defender XDR rebranding](../includes/microsoft-defender.md)]

**Applies to:**
- [Microsoft Defender XDR](https://go.microsoft.com/fwlink/p/?linkid=2118804)

> [!NOTE]
> **Try our new APIs using MS Graph security API**. Find out more at: [Use the Microsoft Graph security API - Microsoft Graph | Microsoft Learn](/graph/api/resources/security-api-overview?view=graph-rest-1.0&preserve-view=true).
> If you're using Microsoft Defender for Business, see [Use the streaming API (preview) with Microsoft Defender for Business](/defender-business/mdb-streaming-api).

[!include[Prerelease information](../includes/prerelease.md)]

## Stream Advanced Hunting events to Event Hubs and/or Azure storage account

Microsoft Defender XDR supports streaming events through [Advanced Hunting](advanced-hunting-overview.md) to an [Event Hubs](/azure/event-hubs/) and/or [Azure storage account](/azure/event-hubs/).

For more information on Microsoft Defender XDR streaming API, see the [video](https://www.microsoft.com/en-us/videoplayer/embed/RE4r4ga).

## In this section

Topic | Description
:---|:---
[Stream events to Azure Event Hubs](streaming-api-event-hub.md)| Learn about enabling the streaming API in your tenant and configure Microsoft Defender XDR to stream [Advanced Hunting](advanced-hunting-overview.md) to Event Hubs.
[Stream events to your Azure storage account](streaming-api-storage.md)| Learn about enabling the streaming API in your tenant and configure Microsoft Defender XDR to stream [Advanced Hunting](advanced-hunting-overview.md) to your Azure storage account.
[Supported event types](supported-event-types.md) | Learn which Advanced Hunting event types the Streaming API supports.

Watch this short video to learn how to set up the streaming API to ship event information directly to Azure Event hubs for consumption by visualization services, data processing engines, or Azure storage for long-term data retention.  
> [!VIDEO https://www.microsoft.com/en-us/videoplayer/embed/RE4r4ga]

## Related topics

- [Use the Microsoft Graph security API - Microsoft Graph | Microsoft Learn](/graph/api/resources/security-api-overview)

- [Overview of Advanced Hunting](advanced-hunting-overview.md)
- [Azure Event Hubs documentation](/azure/event-hubs/)
- [Azure Storage Account documentation](/azure/storage/common/storage-account-overview)
[!INCLUDE [Microsoft Defender XDR rebranding](../includes/defender-m3d-techcommunity.md)]
