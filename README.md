![SpaceX Valuation Model Unbiased Analysis Brian Scott Glassman](https://raw.githubusercontent.com/briang1621/SpaceX-Valuation-Model-Unbiased/refs/heads/main/image1.webp)

# SpaceX-Valuation-Model-Unbiased

## About the Article
The Medium article on the Predict publication highlights the underlying dynamics driving revenue and profitability of the Starlink, space launch, and telecom revenue streams, distilling the complexity of operations down to a few key metrics that drive profitability and growth while explaining the assumptions that predict future growth so readers can understand and make adjustments based on their own views. It also discusses why the moon, Mars, space-based AI compute, and other speculative revenue streams are not included in the valuation—it's a comprehensive and enlightening read: [SpaceX Valuation Model: Estimating Fair Value for an IPO](https://medium.com/predict/spacex-valuation-model-estimating-fair-value-for-an-ipo-17601d5290f2).

## Overview of the Excel Model 
This repository contains a excel based valuation model for SpaceX built from the ground up by modeling revenues and direct operating costs across three major engines of the business: Starlink broadband, SpaceX launch operations, and cell phone telecom services enabled by Starlink. The author provides an accompanying 40-page article that explains the key assumptions and drivers of SpaceX revenue and profitability in a way that is compatible with financial analysis and easy to understand. 

The model breaks revenue and cost estimates for each operation into a near-term period (2025–2029) for greater precision and a long-term period (2030–2036) based on year-over-year growth modeling and into conservative and optimistic models.  The valuation of the enterprise is derived using a revenue-multiple approach, with 2027 used as the base year and both conservative and optimistic cases run for each operating segment to bracket potential outcomes. A 25x revenue multiple was selected based on a comparable IPO analysis. Because reliable segment-level detail is limited, the model currently excludes R&D, administrative, depreciation, and other corporate-level expenses; these will be incorporated as better information becomes available.

The Starlink revenue model is driven primarily by three inputs: subscriber count, subscriber growth rate, and the average subscription price paid by customers. These assumptions flow through to estimate recurring land-based broadband revenue, which represents approximately 98% of Starlink's revenue in the model. The model also includes Starlink's maritime and aircraft connectivity offerings; while these are smaller revenue streams, they are still projected through 2036.

For SpaceX space launch operations, the revenue model centers on cost and launch volume. A key metric is cost per ton delivered to low Earth orbit, and Starship is modeled as a step change that can reduce launch costs per ton by roughly 80% over the existing Falcon 9 launch system. Growth in launch operations is also constrained by a realistic estimate of how many launches can be reasonably achieved in a year, with launch cadence expressed as a function of total payload capacity delivered to low Earth orbit annually.

The telecom services segment is modeled as an additional growth layer enabled by Starlink's direct-to-cell capabilities, with revenue determined by subscriber growth and average customer pricing. This revenue stream is minor relative to Starlink broadband.

Finally, potential future businesses such as space mining, Mars settlement, and AI space-based data centers are argued to be non-viable in the accompanying article and are therefore not included in this valuation model; see the article for additional detail.

## Limited License
This SpaceX Valuation Model herein is provided free of charge under a custom license by Brian Scott Glassman.

You may:
- Use the model for personal, academic, research, or internal business purposes.
- Use the model within financial institutions, including for client-facing analysis.
- Modify the model for internal use or for free distribution to clients.

You may not:
- Sell, resell, license, or sublicense the model.
- Sell, resell, license, or sublicense modified or derivative versions.
- Charge any fee for access to the model or its derivatives.
- Include the model or derivatives in any paid product, service, or subscription.

Important conditions:
- Any distribution to clients must be free of charge.
- Attribution must be retained and displayed first, clearly, and obviously and say:  
  "Original model created by Dr. Brian Scott Glassman"

See the full license text in the [LICENSE](LICENSE.md) file for complete terms and conditions.
----
# **SpaceX Valuation Model: Estimating Fair Value for an IPO**

A Clear Revenue & Profit Forecast Model For Financial Analysts, Prospective Investors, and Space Enthusiasts Investors

## **Outline of Article**

**Executive Summary**

**Section 1: Introduction to the Model**\
1.1 Target Readers\
1.2 No Outside Interests Were Involved\
1.3 Accuracy of the Valuation Model\
1.4 Supporting Excel Revenue, Operating, and Valuation Model\
1.5 Summary of the SpaceX Valuation Model\
1.6 Estimate of Fair Value for SpaceX for an IPO\
1.7 Other SpaceX Valuation Models\
1.8 Limitations on Available Information\
1.9 Helping the Community Build a Valuation Model\
1.10 Expertise of the Author: Dr. Brian Scott Glassman

**Section 2: SpaceX’s Near & Long-Term Revenue Opportunities**\
2.1 SpaceX Revenue Forecast Tables in 2029 and 2036\
2.2 SpaceX Comparable IPOs\
2.3 SpaceX Valuation Results

**Section 3: Projected Valuation of SpaceX’s Starlink Internet Services**\
3.1 Market Position and Competitive Landscape\
3.2 Pricing and Capacity Constraints — Starlink\
3.3 Subscriber Base and Demand Dynamics — Starlink\
3.4 Revenue Estimates for Starlink\
3.5 Unit Economics and Servicing Costs for Starlink\
3.6 Rapid Expansion of Starlink via Access to Large Countries\
3.7 Growth of the Subscriber Base\
3.8 Ancillary Revenues from Aviation and Marine are Small\
3.9 Starlink Expected Revenues in 2029\
3.10 Starlink Revenue Projections for 2036\
3.11 Future Competition for Starlink\
3.12 Major Risks to Starlink

**Section 4: Telecom Services Provided via StarLink**\
4.1 Pricing Model for Telecom via Starlink\
4.2 Number of Subscribers for Telecom via Starlink\
4.3 Valuation of Starlink Telecom Services

**Section 5: SpaceX Launch Services**\
5.1 SpaceX Cost Per Ton to LEO and Margins\
5.2 The Starship Platform is Changes the Game\
5.3 Revenues from Launch Services in 2029\
5.4 Revenue Forecasts for Starship in 2036\
Section 6: Future Speculative Revenue Streams\
6.1 Mars and Moon Missions\
6.2 Space-mining\
6.3 Space-Based AI Compute Data Centers

## **Executive Summary**

This article and analysis present a transparent revenue and valuation forecast model for SpaceX, anchored first by enterprise value estimates derived from a 2027 revenue multiple approach and framed under both conservative and optimistic revenue cases for each major revenue line. Under the conservative case, the implied enterprise value is approximately \$518B, while the optimistic case supports an enterprise value of approximately \$675B, based on a 25× revenue multiple consistent with high growth technology IPO comparables.

All revenue assumptions, operating cost estimates, and valuation calculations are fully documented and available in the accompanying Excel financial model.

These enterprise values are supported by projected 2027 revenues of approximately \$20.7B in the conservative scenario and \$27.0B in the optimistic scenario, built from individual revenue estimates for Starlink internet services, Starlink enabled telecom services, and SpaceX launch activities. The model also extends these conservative and optimistic revenue scenarios forward, with total company revenues forecast to expand meaningfully in 2029 and again in 2036.

The analysis then examines SpaceX’s core operating segments, beginning with Starlink, which is identified as the primary long term value driver. Starlink internet services are projected to scale from approximately \$7B to \$8B in annual revenue by 2027 to roughly \$20–\$29B by 2029, driven by subscriber growth, expanded country level regulatory approvals, and increasing satellite bandwidth capacity. Longer range projections extend to approximately \$53–\$105B in annual revenue by 2036, reflecting a wide but plausible outcome range. The article also evaluates Starlink enabled telecom services; however, this segment remains relatively small, representing less than 1% of projected future revenues.

Finally, the article assesses SpaceX’s launch services business, emphasizing the structural shift enabled by the Starship platform and its ability to dramatically lower the cost to orbit for payloads. Launch revenues are forecast to grow from approximately \$5B in 2025 to \$6.8B–\$8.1B in 2027, expanding further to roughly \$10–\$14B by 2029, with potential to reach approximately \$13B–\$20B by 2036.

Beyond these core businesses, the model explicitly addresses longer term opportunities such as lunar missions, Mars exploration, space mining, and space based compute, concluding that while strategically interesting, they remain too speculative to include in a disciplined valuation today.

Taken together, the analysis positions SpaceX as a company with credible near term revenue visibility, unusually strong long term optionality, and a valuation grounded in clear, auditable financial assumptions rather than narrative driven speculation. An Enterprise valuation in the range of \$500B to \$700B for an upcoming IPO in 2026 would be reasonable.

## **1. Introduction to the Model**

### **1.1 Target Readers**

The target readers for this article are financial analysts, investors, and space enthusiasts. First, financial analysts will understand the business and see the economics of their activities stripped down to the most important factors driving profitability and growth. Second, investors will learn about the major revenue lines and how SpaceX can specifically drive growth in the future. Finally, space enthusiasts will understand how the complex engineering boils down to a few key factors that satisfy customers, investors, and drive profits.

### **1.2 No Outside Interests Were Involved**

The author created this valuation unprompted, unpaid, and has no association with SpaceX or other space-related companies. The author performed this evaluation for their own fair assessment of the potential of the SpaceX IPO with the intent of being fair, unbiased and accurate.

### **1.3 Supporting Excel Revenue, Operating, and Valuation Model on GitHub**

This article is accompanied by an Excel valuation workbook on GitHub with 8 worksheets that detail the revenue assumptions and projections across SpaceX’s major business segments. The workbook models revenues (and direct operating costs) for Starlink broadband, SpaceX launch operations, and Starlink-enabled telecom services, providing segment-level breakdowns that support the analysis in the article, and can be downloaded for free but not resold.

### **1.4 Accuracy of the Valuation Model**

This article is meant to be broad; the accuracy of the private information is hard to verify given that SpaceX is currently private, but the author has taken efforts to do background research from leading online sources tracking SpaceX and its activities and to make grounded estimates and set key assumptions. The model and excel workbook highlights the key assumptions so readers can make adjustments as they see fit.

### **1.5 Summary of the SpaceX Valuation Model**

SpaceX is fundamentally a large bet on global Starlink services and space launch activities, with Starlink accounting for approximately 65% of total revenue in 2025 and roughly 70% of total profits. The analysis presented below shows that it is highly feasible that Starlink could grow from approximately \$9.6B in estimated annual revenue in 2025 to \$20B–\$29B by 2029. Further forecasting shows Starlink could possibly reach \$50B–\$105B in global revenues by 2036, with operating margins as high as 85% due to economies of scale and advances in satellite bandwidth capacity; hence, this is a very valuable revenue stream.

Similarly, SpaceX’s launch activities will increasingly be driven by Starship and could generate approximately \$10B–\$14B in revenue by 2029, scaling to roughly \$14B–\$22B by 2036. With the help of the new launch platform, Starship (7x launch capacity), margins could move from an estimated profit margin of 55% to potentially 80%. Telecom services provided by Starlink also represent another revenue stream; these are estimated to be in the tens of millions until 2029 and grow to potentially \$20B by 2036.

In aggregate, SpaceX has the potential to become an exceptionally valuable and profitable company if it continues its record of operational excellence and low-cost execution.

From a valuation standpoint, SpaceX is best analyzed using a revenue multiples model. Under this perspective, projected revenues from 2027 and a multiple of 25x selected from comparable IPOs put today’s value between **\$518B and \$675B.** Given the potential for monopoly-like positioning in both global satellite internet and launch services, this estimate seems reasonable. However, space operations do have significant risks, and going higher than a 25x multiple seems a bit excessive.

### **1.6 Estimate of Fair Value for SpaceX for an IPO**

This author would push for a lower valuation of 20× to 25× of 2027 forecasted revenues. This is due to limited financial information, risks of space operations, risks associated with the CEO’s public image and popularity, and the market’s experience valuing companies heavy in space operations.

### **1.7 Limitations on Available Information**

There is limited verification of financial costs, as SpaceX is a private company; it is expected that the IPO filing will clarify this. Risks due to space operations include proving out the Starship platform and space-based risks associated with large satellite constellations, like solar flares impacting the network.

Additionally, Elon Musk is a visionary and also controversial figure; love or hate him, one can obviously see that Tesla’s stock price was impacted due to the myriad of political attacks against him by politicians, left leaning media, Delaware courts rulings, and even the FAA delaying launches under Biden, and this must be factored in.

Finally, the market has limited experience valuing mega-cap satellite and space launch operations. Currently traded companies as of January 2026 are SATS (\$35.5B), PL (\$9B), VSAT (\$6.2B), IRDM (\$2B), and SPIR (\$410M), with none operating their own space launch services to dramatically lower launch costs.

Again, This author would advocate for an IPO valuation toward the lower end of this range, 20× to 25×, around \$500B and \$675B.

### **1.8 Other SpaceX Valuation Models**

ARK Invest has an open-source valuation model for SpaceX on GitHub; however, in this author’s opinion, it is not realistic. First, it is overly detailed and represents dramatic overkill due to its complexity, and second, it values opportunities such as Moon and Mars colonization at trillions of dollars. Specifically, when a stock is over-modeled, such as through extensive Monte Carlo simulations, there is a high risk of attributing growth and revenue outcomes to faulty assumptions. Second, the Moon and Mars opportunities mentioned below are, in the author’s view, a minimum of 10 years away from generating any revenue. Finally, with ARK Invest being a fund that holds SpaceX, there is a major conflict of interest in ARK Invest’s publicly released valuation.

### **1.9 Helping the Community Build a Valuation Model**

Ultimately, the investment community must build its own valuation models for SpaceX, and industry experts tend to converge on clear, simple metrics that directly drive revenue and profitability. Note this valuation appears simple, but it is informed by substantial analysis not shown herein. Further, it was built in the hoped that this clear yet realistic revenue estimation methodology will help guide others in further refining their own estimates.

### **1.10 Expertise of the Author: Dr. Brian Scott Glassman**

I have been following SpaceX operations fervently for 15 years. As a trained senior mechanical engineer with a Ph.D. in Business and Innovation Management, I understand the technical details of the company’s operations and engineering and place them in perspective in terms of their true business value. In short, fancy engines or large rocket ships are nice, but they ultimately must serve the goal, which is to reliably beat the competition, generate profitable revenue, and fuel growth, hence my focus to highlight these aspects.

## **2. SpaceX’s Revenue Forecast Results**

This analysis focuses on the high revenue opportunities for SpaceX with estimates focused on the valuation year taken in 2027, and then projected 10 years (2036) from the current day.

To accomplish this, the article will start by reviewing SpaceX’s near-term revenue opportunities from largest to smallest, beginning with Starlink Internet Services, followed by Space Launch Services, and then telecom services provided by Starlink. Current, non-revenue-generating opportunities are also discussed, such as the Moon, Mars, space mining, and space-based AI data centers.

### **2.1 SpaceX Revenue Forecast Tables in 2029 and 2036**

**Below is the author’s estimates of SpaceX’s Revenue Projections in 2025 to 2029.**

The second is the Optimistic Scenario, with 2027 highlighted as the basis for the enterprise valuation.

![SpaceX Revenue Projections 2025 to 2036 starlink, space launch, telecom, and profit](https://raw.githubusercontent.com/briang1621/SpaceX-Valuation-Model-Unbiased/refs/heads/main/image2.webp)

Image: SpaceX Conservative Revenue and Profit Projections: 2025 to 2036

SpaceX Conservative Revenue and Profit Projections: 2025 to 2036

![SpaceX Optimistic Revenue and Profit Projections: 2025 to 2036](https://raw.githubusercontent.com/briang1621/SpaceX-Valuation-Model-Unbiased/refs/heads/main/image3.webp)

The second is the Optimistic Scenario for revenue and profit projections.


SpaceX Optimistic Revenue and Profit Projections: 2025 to 2036

### **2.2 SpaceX Comparable IPOs**

The valuation for SpaceX is based on a 2027 revenue multiple approach, using a selected multiple of 25x. This multiple is informed by large IPOs of high-growth, comparable technology companies, including Anduril Industries at 30.5x, Cloudflare at 27.6x, CrowdStrike at 20.6x, and Slack Technologies at 21.0x revenue multiples at IPO, with an average multiple of approximately 24.9x. Based on these comparables, a 25x multiple represents a reasonable and balanced assumption for valuing a category-defining company like SpaceX.

The author selected 2027 as the base year because NTM+1 is the standard convention for high-growth IPO valuations, balancing near-term visibility with growth trajectory while remaining within the credible forecasting window institutional investors accept.

### **2.3 SpaceX Valuation Results**

Moving on to the estimated enterprise value, under a conservative scenario, projected 2027 revenues of \$20.7B and a 25x revenue multiple result in a base-case enterprise value of approximately \$518.3B. Under the optimistic scenario, higher projected 2027 revenues of \$27.0B combined with the same 25x multiple imply a valuation of approximately \$674.5B.

![SpaceX Conservative Valuation Based on 2027 Revenues Multiple Approach](https://raw.githubusercontent.com/briang1621/SpaceX-Valuation-Model-Unbiased/refs/heads/main/image4.webp)


SpaceX Conservative Valuation Based on 2027 Revenues Multiple Approach


![SpaceX Optimistic Valuation Based on a 2027 Revenue Multiple Approach](https://raw.githubusercontent.com/briang1621/SpaceX-Valuation-Model-Unbiased/refs/heads/main/image5.webp)

**SpaceX Optimistic Valuation Based on a 2027 Revenue Multiple Approach**

Again, the author does not believe a multiple higher than 25x is warranted given limited financial disclosure, the inherent risks of space operations, risks associated with the CEO’s public image, and the market’s limited experience valuing space-based operations companies.

## **3. Revenues from Starlink Internet Services**

### **3.1 Market Position and Competitive Landscape**

Starlink offers a high-profit revenue stream with little to no comparable competition. Competitors such as HughesNet and Viasat may advertise download speeds of up to 100 Mbps, but in practice they fall far short due to latency of 0.5 to 1 second. By comparison, Starlink offers communication speeds of around 200 Mbps and as high as 300Mbps with approximately 0.045 seconds of latency, which consumers will always favor ([Link to Starlink Speed Specs](https://starlink.com/legal/documents/DOC-1470-99699-90)).

In addition, these competitors’ satellite internet services are geographically limited, whereas Starlink offers near-global coverage, excluding polar regions; however, availability in certain countries remains pending regulatory approval. Most importantly, Starlink has secured access in regions with high-value customers (see [their coverage map](https://starlink.com/map)).

As of 2027, Starlink operates approximately 9,400 satellites in low Earth orbit, which can be viewed in real time on a live satellite map. These satellites provide internet service via a user installed dish that communicates with low Earth orbit satellites, which then relay data to an Earth based ground station typically located within 200 miles of the customer. Over oceans and remote regions, data is relayed through high bandwidth laser links between multiple Starlink satellites until it reaches a ground station, resulting in slightly higher latency.

### **3.2 Pricing and Capacity Constraints**

Prices currently range from \$50 to \$150 per month in the United States, with new \$50 plans released in January 2026. Pricing is tiered and based on download speeds. More importantly, the number of customers that can be served is hard limited by total available satellite bandwidth and the number of satellites in orbit. As a result, deploying next generation Starlink satellites with higher capacity will be a primary driver of expanded internet availability, increased speeds, and future subscriber growth.

### **3.3 Subscriber Base**

Outside of dense urban centers, Starlink’s current deployment has been able to mostly keep pace with rural demand. SpaceX does not regularly publish official subscriber numbers, but in the event of an IPO, this metric will become public and closely scrutinized. SpaceX announced in Nov 2025 that they reached 8 million active subscribers.

### **3.4 Revenue Estimates for Starlink**

Subscriber statistics are tracked at [IDEMEST](https://idemest.com/reports/starlink-country-data-tracker/) but this report was not verified by the author. Revenue figures are estimates and are not officially published. For 2024, estimated revenue is approximately \$8.2B. With roughly 4.63 million subscribers, this implies an average annual subscription price of about \$1,700 per user, or approximately \$150 per month. With 8 million subscribers in November 2025 and the same pricing, expected revenue would be approximately \$9.6B. However, the author expects the average subscription price per customer to decline as Starlink introduces lower cost plans and bandwidth capacity increases.

### **3.5 Unit Economics and Servicing Costs**

The largest cost for servicing customers is the cost of maintaining and growing the Starlink constellation of satellites. The cost to service each subscriber is fairly difficult to calculate and not published by SpaceX. Here SpaceX has some excellent developments to lower costs per customer served like increase bandwidth capacity with next generation Starlink satellites, lower launch costs due to Starship.

As a rough estimate, a Falcon 9 launch costs SpaceX approximately \$45M and is reported to carry about 29 Starlink satellites each costing \$200k, implying roughly \$1.75M per satellite in launch costs. Second generation (V2) Starlink satellites are estimated to cost approximately \$800K each to manufacture and weigh about 800 kg, allowing Falcon 9 to deploy roughly 25 per launch with a deploy cost of \$2.6M per V2 satellite. Unpublished estimates suggest a capacity of approximately 1,000 users per first generation satellite and about 4,000 users per second generation satellite.

Using second-generation Starlink satellites as a reference, this implies a total upfront cost of about \$2.6M per satellite, which amortized over five years equates to approximately \$130 per user per year, or about \$11 per month per user. This represents roughly 7% of the average annual subscription fee. Users also require a satellite dish on their premises, which is included free at signup and retails for \$299, though it is likely to cost SpaceX closer to \$100.

The cost to service a customer with internet via Starlink is expected to decline significantly. The author estimates it could fall toward roughly \$2 per user per month as satellite user capacity improves and future satellites are deployed using the lower cost Starship launch platform. Accordingly, the author expects a portion of revenue, approximately 10%, to be allocated to launching new Starlink satellites, managing the satellite constellation, and operating land based ground stations.

### **3.6 Rapid Expansion of Starlink via Access to Large Countries**

The rapid addition of large subscriber bases will be driven by market openings in large countries pending regulatory approval such as India, Pakistan, Vietnam, Thailand, Morocco, Egypt, and Turkey. Note that China does not look like a likely prospect due to preferred government internet controls. These agreements are likely to add between big segments of customers 2 million and 10 million additional users over the next three years. At a discounted average subscription price of \$100 per month, this would contribute approximately \$2.4B to \$12B in additional annual revenue after 3 years which is quite sizable.

### **3.7 Growth of the Subscriber Base**

Some online sources cite annual subscriber growth of approximately 40% in developed markets, but this appears aggressive. A more conservative assumption is declining growth rates over time. Starting from a base of 8 million subscribers in November 2025 and assuming conservative 20% annual growth from 2025 to 2029 results in approximately 16.6 million subscribers, while an optimistic 25% growth rate results in approximately 19.5 million subscribers.

Taken together, over a three year horizon, average subscription prices may decline modestly to approximately \$100 to \$125 per month in order to attract more customers. With a subscriber base of 16.6 million to 19.5 million users, this implies annual Starlink revenues in 2029 in the range of approximately \$19.9B to \$29.3B.

For projections from 2030 to 2036, annual growth rates of 15% and 20% were assumed for conservative and optimistic cases, respectively, yielding revenues in 2036 between approximately \$53B with 40 million subscribers and \$105B with 70 million subscribers. These estimates may be overstated, as growth rates that far into the future are inherently difficult to forecast, although reaching 70 million global subscribers is feasible given strong worldwide demand for internet services and continued development across many nations.

### **3.8 Ancillary Revenues from Aviation and Marine are Small**

Additional revenue from aviation and maritime customers is meaningful but relatively small compared with core land based consumer internet subscriptions. As of 2025 there are roughly 370 cruise ships worldwide, with equipped ships typically using two to four Starlink terminals. Pricing ranges from \$4,000 to a negotiated average of approximately \$8,000 per month per ship. It is estimated that 100% of cruise ships will be equipped with Starlink by 2027, generating approximately \$35 million in annual revenue.

Similarly, long haul commercial aircraft represent another opportunity. With approximately 4,000 aircraft globally equipped at \$4,000 per month, this segment would generate approximately \$192 million in annual revenue in 2029, assuming 100% saturation that year. From 2029 to 2036, growth rates are estimated at 2% to 3%, broadly in line with fleet growth.

Short haul aircraft are less attractive candidates for Starlink upgrades due to higher installation costs and shorter flight times, which reduce passenger willingness to pay for in flight internet access outside of premium airline carriers. However, with 10% to 15% saturation expected by 2029 and a lower monthly subscription rate of \$2,000, revenues are estimated at \$48 million to \$72 million in 2029. Overall, both maritime and aviation Starlink revenues are expected to remain approximately 1% of land based revenues and may not be material enough to warrant detailed modeling by other analysts.

### **3.9 Starlink Expected Revenues in 2027 & 2029**

Starlink appears to be a strong cash generator, and given the limited public information available on costs, it is likely highly profitable, with estimated operating margins of approximately 70% to 85%. Under these assumptions, 2027 revenues are projected to range from \$13.9 billion to \$18.8 billion under conservative and optimistic scenarios, while 2029 revenues are estimated at \$20.1 billion to \$29.6 billion under similar assumptions.

### **3.10 Starlink Revenue Projections for 2036**

Assuming slower annual subscriber growth from 2029 to 2039, it is reasonable to project 2036 annual revenues in the range of \$53 billion to \$105 billion for the conservative and optimistic scenarios respectively, with operating margins of approximately 70% to 84%. The wide revenue range reflects uncertainty in annual subscriber growth, which was modeled linearly at 15% to 20% for convenience, though in reality it is more likely to taper lower year over year.

Consequently, this would make Starlink a highly valuable revenue stream, but again these estimate are harder to project.

### **3.11 Future Competition for Starlink**

There is current competition for Starlink, as noted above, from Viasat and HughesNet, but the largest future entrant that could pose a challenge is Amazon LEO. Amazon is currently launching satellites at a cadence of 27 per month and has deployed 180 satellites, or approximately 6% of the total. The FCC requires 1,618 satellites to be deployed for operations; therefore, based on the timing of this article, it would take roughly 4.4 years for the system to become operational, unless the deployment rate increases significantly via Blue Origin’s New Glenn rocket. Unfortunately, New Glenn has only completed one test-to-orbit flight to date.

Another potential future competitor is China, which could deploy a large constellation. The author believes these systems will remain primarily domestic or regionally limited, as most foreign governments in developed nations have major privacy and security concerns about routing their internet data through a Chinese data carrier. Developing nations will be less concerned, and a low price point would put China in a strong position with customers in these countries.

Again, barriers to entry in satellite internet are extremely high. Replicating a high-bandwidth, low-latency, low-Earth-orbit internet constellation would require tens of billions of dollars in satellite manufacturing and launch costs and would be most constrained by limited launch vehicle availability and cadence.

Blue Origin also plans to develop a competing satellite internet system for governments and data centers, the TeraWave space-based network, with an initial deployment schedule beginning in Q4 2027. The timeline to achieve meaningful scale remains extended. Assuming they use their top-line New Glenn launch vehicle’s approximately 45 metric ton capacity to low Earth orbit and satellite specifications broadly comparable to Starlink V2 at roughly 800 kilograms per satellite, approximately 50 TeraWave satellites could be deployed per launch.

To reach the announced constellation size of 5,280 satellites in low Earth orbit would therefore require on the order of 106 launches. Given that New Glenn has completed only a single test flight to date, it is reasonable to estimate that it will take a further four to seven years from the end of 2027 to complete constellation deployment, implying a 2032 to 2034 completion timeframe.

Despite the mentioned new entrants, Starlink is expected to have achieved significant global penetration, creating a decent competitive moat. Notably, Blue Origin is considering contracting SpaceX to launch a portion of its satellites, which could accelerate that timeframe. As a result, the author believes SpaceX is unlikely to face meaningful near-term competition from rival satellite internet constellations.

### **3.12 Major Risks to Starlink**

However, competitive dynamics are not the only risk. Space is an inherently hostile operating environment, where low probability but high impact events such as extreme solar activity or debris cascade scenarios, often referred to as Kessler Syndrome, could disrupt satellite operations, forcing replacement satellites to be deployed and potentially reducing total network bandwidth.

## **Section 4. Telecom Services Provided via StarLink**

Telecom ground coverage for cell phones is generally good to excellent in large cities across the world due to the significant profits generated from offering 5G and 4G cellular services (see the [cell phone coverage global map](https://verizon.cellmaps.com/)). However, outside of major population centers, especially in developing nations, cell phone coverage becomes far more challenging. To erect a cell phone tower, there must be sufficient local traffic to justify the expense; as a result, many rural areas in less developed nations are not currently covered and are unlikely to be covered in the future.

Consequently, SpaceX launched a telecom service offering in 2025, enabled by newer generations of Starlink satellites that can support modern cell phones via the 4G/LTE protocol at 5 to 10Mbps. This allows near global coverage for phone calls and messaging, albeit with lower bandwidth data, and opens vast, previously underserved rural populations to cellular coverage. Furthermore, the number of customers that can be served concurrently per satellite is estimated to be significantly higher than for land based internet services in the 3,000 to 10,000 range, and thousands of SMS per second.

### **4.1 Pricing Model for Telecom via Starlink**

The pricing and business model will most likely take the form of an add-on service offered through existing cellular providers in each country and may be priced by the carriers in the range of \$2–\$10 per month, depending on the country. SpaceX is likely to get 30% to 50% of the local cell carriers price. It is estimate that SpaceX will get \$2/month or \$24 per year per subscriber is taken as the conservative case with \$3 or \$36 per year as the optimistic case.

### **4.2 Number of Subscribers for Telecom via Starlink**

The range of potential subscribers for Starlink’s Telecom services is difficult to estimate today, as it depends heavily on the quality of service, whether country-based telecom providers and national governments choose to promote or block the offering, the affordability of the service for rural populations, and if SpaceX puts a significant marketing push behind this service line. For example, a country such as Brazil alone could ultimately support millions of rural subscribers.

### **4.3 Valuation of Starlink Telecom Services**

Shifting to the valuation, for scale, 8 million subscribers at \$24 per year would generate approximately \$192M in annual revenue, while 100 million subscribers would generate roughly \$2.4B. Even at very large subscriber counts, this revenue stream would be small in comparison with Starlink’s core internet service revenues.

For 2027 the revenue will be less than \$5 million. However, for 2029, the conservative case estimates roughly 8 million subscribers generating \$194 million in revenue, while the optimistic case assumes 15 million subscribers generating approximately \$540 million. As with other non core segments, this revenue remains small relative to Starlink’s primary services and may therefore receive limited marketing emphasis. In 2036, revenue projections range between \$500M to 2.5B.

## **Section 5. SpaceX Launch Services**

Valuing SpaceX’s launch services is complex because of an upcoming shift to a new launch vehicle named Starship. In 2025, SpaceX performed 170 launches, most with Falcon 9; of those, 75% did not generate direct revenue because they deployed Starlink satellites, but 42 of them were paid for by clients. With an average launch cost of \$70M, rough math shows that it could have generated launch-related revenues of \$2.94B, but published revenue for 2024 shows [\$4.2B in launch services](https://payloadspace.com/estimating-spacexs-2024-revenue/). So in reality, 2025 launch revenues are probably closer to \$5B. The additional revenues would be do to government contracts, manned missions, and priority missions priced at 2–4X normal due to [expensive launch integration services. ](https://spaceexplored.com/spacex-launches-2025/)However, with margins around 40% to 50%, expect \$2.5B gross profit from launch operations from Falcon 9 in 2025.

For financial analysts, the core economic metric to monitor is the cost per metric ton deployed to low Earth orbit (LEO), as this provides a consistent baseline for comparing launch providers across countries. Deployments to medium Earth orbit, high Earth orbit, or geosynchronous orbit are effectively derived from this baseline, reflecting reduced payload capacity relative to LEO for the same launch vehicle.

The second number to watch is the launch cadence, or launches per year, as that dictates how much tonnage can be put into space. SpaceX performed [170 launches in 2025](https://spacestatsonline.com/launches/year/2025), with the next closest being China’s CASC with an impressive 93 launches. Note that growth in launch cadence is slow, as manufacturing and readying rockets for launch is a lengthy procedure.

### **5.1 SpaceX Cost Per Ton to LEO and Margins**

After a detailed analysis not shown here, the SpaceX Falcon 9 launch platform is effectively priced for customers at around \$3M to \$5M per metric ton to low Earth orbit (cost variation is due to payload configuration variations) with one rocket putting up 22.8 metric tons. The author’s estimates put margins at 40%, so one metric ton costs SpaceX between \$1.2M to \$2M to launch to an equivalent LEO.

### **5.2 The Starship Launch Platform is Changes the Game**

Starship, due to its large size and reusability, fundamentally disrupts the launch industry by putting 150 metric tons to LEO or 6.5x Falcon 9 in one launch. Based on this author’s internal calculations, Starship could dramatically lower the cost to Low Earth Orbit to approximately \$150k per ton while deploying 150 tons per launch if fully reusable; about \$300k per ton while deploying 200 tons if only the booster is reused; and roughly \$450k per ton while deploying 250 tons if the entire vehicle is expended.

Starship is entering version 5, and has proven in the last flight to complete its mission objectives. The \$5B to \$10 in R&D expenses for its development are now shifting toward a rapid manufacturing line for producing hundreds of Starships. Per unit cost for a single Starship are not public but can be estimated at approximately \$100M (\$50M for the upper stage and \$50M for the lower stage), with an additional fixed \$8M per launch for fuel and support costs. These assumptions underpin the payload cost estimates in the first paragraph.

With per-ton launch costs measured in the hundreds of thousands rather than millions, Starship fundamentally changes the economics of launch. This gives SpaceX the ability to aggressively undercut competitors while retaining pricing control. For example, reducing customer pricing by half from \$3M per ton to \$1.5M per ton would still represent an approximate 90% gross margin for SpaceX, assuming an underlying cost of \$150k per ton for a fully reusable Starship.

### **5.3 Revenues from Launch Services in 2029**

Currently, SpaceX launches a Starship approximately once every three months, but with two launch towers at its Texas facility, a monthly cadence is achievable. It is expected that Starship could reach a launch rate of twice per month by 2027. At that pace, and assuming a hypothetical price of \$1M to \$1.3M per metric ton to low Earth orbit, annual Starship launch revenue would be approximately \$3.6B. With additional customer integration and mission-specific service charges, total revenue could reasonably increase to roughly \$6B. Given the significantly lower marginal launch costs, operating margins could expand to approximately 85%, implying retained profits of around \$5B.

For 2027, the projections assume approximately 10 paid Starship launches and between 35 and 45 paid Falcon 9 launches, generating combined launch services revenue of roughly \$6.8B to \$8.1B. By 2029, total launch volume could increase by approximately twofold as lower launch prices stimulate incremental demand, allowing launch services revenue to expand to an estimated \$10B to \$14B annually.

### **5.4 Revenue Forecasts for Starship in 2036**

Estimating future launch cadence or the incremental demand generated by lower launch pricing is inherently difficult. If the U.S. government were to pursue its own high speed Starlink-like satellite constellation, dubbed “[Starshield](https://www.spacex.com/starshield)” equipped with high resolution radars and optics for use by the US air-force, this alone could represent a \$10B opportunity on top of existing launch demand. Conservatively, launch revenues could reach approximately \$18B by 2036, roughly doubling from 2029 levels, while maintaining profit margins near 80% due to Starship’s exceptionally low operating costs.

## **Section 6: Future Speculative Revenue Streams**

### **6.1 Mars and Moon Missions**

If the U.S. government were to fully fund a lunar base, it could represent a profitable endeavor for SpaceX. However, extensive data collected from rovers over more than a decade strongly indicate that both the Moon and Mars are largely barren environments. Claims to the contrary are optimistic beyond the evidence currently available.

Hence, It is this author’s view that SpaceX’s public emphasis on Mars missions serves primarily as a long-term motivational narrative for engineers, investors, and the public rather than a near-term revenue opportunity.

### **6.2 Space-mining**

This opportunity remains highly speculative. While asteroid mining could theoretically yield hundreds of billions of dollars in rare-earth minerals, it is likely at least a decade away from assessing technical and economic viability through robotic missions to asteroids. As such, space mining cannot be responsibly incorporated into any current valuation estimates.

### **6.3 Space-Based AI Compute Data Centers**

The author is skeptical about deploying space-based compute and AI data centers as large satellite constellations or as couple massive single deployments. In this concept, Elon proposes using highly effective space-based solar arrays to eliminate ground-based electricity bills, office and land leasing costs, and government taxes, but this simply trades operating costs for expensive, heavy satellites that are difficult to maintain and expensive to launch.

Put plainly, it would require deploying the most power-hungry, heat-generating computing satellite ever built, with power need roughly factor of 100x the next closes satellite, into the hostile environment of space.

Any space-based AI cluster must also compete, on an ROI basis, with land-based data centers. Lets take the large AI satellite approach, a space-based 20 MW solar array might weigh around 300 tons to power a decent-sized space-based AI compute cluster, while the compute hardware itself could weigh another 700 tons. Even under an highly optimistic assumption of \$100k per ton to orbit using Starship, launch costs alone would be about \$100M, merely to avoid roughly \$15M-\$40M per year in electricity costs, office and land leasing costs, and government taxes, in the United States. This estimate does not even include the cost of the specialized hardware being launched.

If we consider the smaller AI satellite approach, at roughly 4x the size of the Starlink V2 satellites (then approximately 3,200 kg each), the economics may work out better. A Starship could launch 45 satellites at once, and governments and defense systems would likely pay a premium for 4x to 8x land-based AI compute costs in systems that offer privacy and are resistant to tampering or sabotage. Here, each satellite would have its AI compute reserved, guaranteeing an immediate return on investment. However, cost-sensitive consumer and business applications will be less interested at those higher price point. Consequently, calculating the revenue stream AI space based AI compute of Starlink will be difficult without specifications for a Starlink AI satellite for comparison, as there are too many design variables to consider. Hopefully, those specifications will be released soon.

No matter how you look at it, the compute costs of AI in space will be higher, but the other benefits will be very attractive to some customers. Innovation is difficult to predict, but over several years the cost of space-based AI compute would come down. However, the author does not expect it to fall below terrestrial AI compute costs, which is likely to see rapid innovation, including improvements in AI compute efficiency and reductions in electricity and other associated costs via simple negotiations.

## **About the Author Dr. Brian Scott Glassman**

The author is a fan of space operations and closely follows developments at SpaceX and other space companies. He holds a Ph.D. in Product Innovation from Purdue and three engineering degrees. He currently specializes in AI strategy and software. He can be contacted on [LinkedIn](https://www.linkedin.com/in/drbrianglassman/), and his written work can be viewed on his personal website, [https://DrBrianGlassman.com](https://DrBrianGlassman.com/).

