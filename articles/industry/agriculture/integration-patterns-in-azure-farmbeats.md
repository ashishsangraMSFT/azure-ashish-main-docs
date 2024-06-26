---
title: Azure FarmBeats Architecture
description: Describes the architecture of Azure FarmBeats
author: gourdsay
ms.topic: article
ms.date: 11/29/2023
ms.author: angour
---

# Integration patterns

Azure FarmBeats is a business-to-business offering, available in Azure Marketplace. FarmBeats enables aggregation of agriculture datasets across providers, and generation of actionable insights by building Artificial Intelligence (AI) or Machine Learning (ML) models by fusing the data sets.

> [!IMPORTANT]
> Azure FarmBeats is retired. You can see the public announcement [**here**](https://azure.microsoft.com/updates/project-azure-farmbeats-will-be-retired-on-30-sep-2023-transition-to-azure-data-manager-for-agriculture/).
>
> We have built a new agriculture focused service, it's name is Azure Data Manager for Agriculture and it's now available as a preview service. For more information see public documentation [**here**](../../data-manager-for-agri/overview-azure-data-manager-for-agriculture.md) or write to us at madma@microsoft.com. 

![Project Farm Beats](./media/architecture-for-farmbeats/farmbeats-architecture-1.png)

The following sections describe the integration pattern for Azure FarmBeats.

## Why integrate with Azure FarmBeats?

This section is focused on partners who want to integrate their data systems (like sensors, drones, weather stations) into Azure FarmBeats.

Azure FarmBeats is an extensible offering, which enables agricultural businesses to add their different historical and real-time agricultural datasets into a single platform. Azure FarmBeats helps an agricultural business to normalize, contextualize, and aggregate its data in the context of a farm.

By becoming a data partner with Azure FarmBeats, you can open your systems to wider adoption, and reach out to more customers with your data offerings. Azure FarmBeats provides an extensible API layer called the Datahub, which helps you ingest data from your devices systematically and into a standardized schema.

Once the data is available within your customers’ Azure FarmBeats instance, your customers can build richer analytics and tools on top of your data.

## Next steps

For more information about sensor data integration, see [sensor data integration](sensor-partner-integration-in-azure-farmbeats.md) and for imagery partner integration, see [imagery partner integration](imagery-partner-integration-in-azure-farmbeats.md).
