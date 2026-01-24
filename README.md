# SpaceX-Valuation-Model-Unbiased

This repository contains a excel based valuation model for SpaceX built from the ground up by modeling revenues and direct operating costs across three major engines of the business: Starlink broadband, SpaceX launch operations, and cell phone telecom services enabled by Starlink. The author provides an accompanying 40-page article that explains the key assumptions and drivers of SpaceX revenue and profitability in a way that is compatible with financial analysis and easy to understand. 

The model breaks revenue and cost estimates for each operation into a near-term period (2025–2029) for greater precision and a long-term period (2030–2036) based on year-over-year growth modeling and into conservative and optimistic models.  The valuation of the enterprise is derived using a revenue-multiple approach, with 2027 used as the base year and both conservative and optimistic cases run for each operating segment to bracket potential outcomes. A 25x revenue multiple was selected based on a comparable IPO analysis. Because reliable segment-level detail is limited, the model currently excludes R&D, administrative, depreciation, and other corporate-level expenses; these will be incorporated as better information becomes available.

The Starlink revenue model is driven primarily by three inputs: subscriber count, subscriber growth rate, and the average subscription price paid by customers. These assumptions flow through to estimate recurring land-based broadband revenue, which represents approximately 98% of Starlink’s revenue in the model. The model also includes Starlink’s maritime and aircraft connectivity offerings; while these are smaller revenue streams, they are still projected through 2036.

For SpaceX space launch operations, the revenue model centers on cost and launch volume. A key metric is cost per ton delivered to low Earth orbit, and Starship is modeled as a step change that can reduce launch costs per ton by roughly 80% over the existing Falcon 9 launch system. Growth in launch operations is also constrained by a realistic estimate of how many launches can be reasonably achieved in a year, with launch cadence expressed as a function of total payload capacity delivered to low Earth orbit annually.

The telecom services segment is modeled as an additional growth layer enabled by Starlink’s direct-to-cell capabilities, with revenue determined by subscriber growth and average customer pricing. This revenue stream is minor relative to Starlink broadband.

Finally, potential future businesses such as space mining, Mars settlement, and AI space-based data centers are argued to be non-viable in the accompanying article and are therefore not included in this valuation model; see the article for additional detail.



## Limited License

This SpaceX Valuation Model is provided free of charge under a custom license by Brian Scott Glassman.

You may:
- Use the model for personal, academic, research, or internal business purposes
- Use the model within financial institutions, including for client-facing analysis
- Modify the model for internal use or for free distribution to clients

You may not:
- Sell, resell, license, or sublicense the model
- Sell, resell, license, or sublicense modified or derivative versions
- Charge any fee for access to the model or its derivatives
- Include the model or derivatives in any paid product, service, or subscription

Important conditions:
- Any distribution to clients must be free of charge
- Attribution must be retained:  
  "Original model by Brian Scott Glassman"

See the full license text in the [LICENSE](LICENSE.md) file for complete terms and conditions.
