---
title: Production order cost estimation
description: Learn about production cost estimation, which provides the capacity consumption costs of producing items in the planned production order quantity.
author: prasungoel
ms.author: prasungoel
ms.reviewer: kamaybac
ms.search.form: BOMCalcTrans, InventCostTrans, ProdCalcTrans, ProdTableJour, ProdTableListPage
ms.topic: how-to
ms.date: 03/17/2025
ms.custom: 
  - bap-template
---

# Production order cost estimation

[!include [banner](../includes/banner.md)]

This article provides information about production cost estimation. Production cost estimation provides the projected material and capacity consumption costs of producing an item in the planned production order quantity.

After you create a production order, you must estimate production costs. The purpose is to estimate item and route consumption for the production process, because these estimates are used as the basis for subsequent scheduling and production processes.

## Production cost estimation

Estimates of production costs are based on the following information:

- The quantity on the production order
- The components on the production bills of materials (BOMs)
- The routing operations in the production route
- The indirect costs that apply to the components and operations
- The active cost data as of the calculation date

If there's a phantom line item on the production BOMs, the calculations reflect the phantom’s components and route operations. You can use the estimation task to recalculate estimated costs so that they reflect updated information. For example, the updated information might be changes to the quantity on the production order, the components on the production BOMs, the routing operations in the production route, the indirect costs that apply to these components and operations, or the active cost data as of the recalculation date. The calculations of estimated cost also suggest a sales price for the production item, based on a cost-plus-markup approach. The calculations of estimated cost can optionally apply to reference orders that reflect other production orders that are linked to the production order.

## View the estimated costs

After you run estimation, you can view the results on the **Price calculation** page. The estimation calculates the following values:

- **Production cost** – The production cost is the top line of the estimate. It shows the complete cost of running the production order and the total sales price for the production. It's the sum of all the cost lines on the estimate.
- **Route or resource costs** – Route or resource costs are the costs for the production operations. They include the cost of elements such as setup time, run time, and overhead.
- **Material costs** – Material costs are the costs and prices of the BOM components that are required in order to produce the item. These costs were previously established and entered into the system.

## Other uses of cost estimation

A cost estimate also provides the following information:

- Meaningful price quotations
- Estimates of the profitability of the order
- Estimates of raw material usage
- Comparisons of cost information from previous productions
- Budget and forecasting information
- Estimates of the production size that is required in order to maintain a particular cost

[!INCLUDE[footer-include](../../includes/footer-banner.md)]
