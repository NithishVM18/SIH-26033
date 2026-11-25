# Smart India Hackathon Workshop
# Date:25-11-2026
## Reference Number:26018775
## Name:NITHISH V M 

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
KisanSetu is a farmer-first digital marketplace where farmers and FPOs can list their produce for consumers, shops, restaurants, and other bulk buyers.

Farmers or FPO staff create a listing with the crop, variety, quantity, harvest date, quality grade, pickup location, and asking price. Buyers can compare listings and place orders. Before accepting an order, farmers can see the expected payment and any platform, packing, or delivery charges.

Farmers with small quantities can choose to combine their produce through an FPO for a shared sale or delivery route. Each lot remains traceable to its farmer or group. Farmers decide whether to accept an offer, and buyers can agree on quality and grading requirements before placing larger orders.

The platform supports local-language screens, voice or SMS updates, and assisted listings through FPO staff or local facilitators. Forecasts and route plans are recommendations; farmers keep control over their prices, quantities, and sales decisions.

## Technical Approach
- Marketplace: Build a mobile-friendly website and optional Android app with farmer and buyer accounts, produce listings, search, orders, confirmations, receipts, and status updates.
- Technologies: A prototype could use React or Flutter for the interface, Python with FastAPI for application services, and PostgreSQL with PostGIS for listings, orders, and locations.
- Demand forecasting: Start with a basic forecast using past orders, season, local market information, and buyer interest. Show estimates as ranges, not guaranteed prices. Improve forecasts as reliable pilot data becomes available.
- Route planning: Use pickup and delivery locations, order sizes, vehicle capacity, and delivery windows to group compatible orders and suggest efficient routes. Allow a dispatcher to adjust the suggested plan.
- Access and trust: Provide local-language screens, assisted onboarding, consent-based data collection, secure accounts, and records of order changes. Never ask users to share a bank PIN or one-time password.
Prototype flow: Farmer or FPO lists produce → buyers compare listings and place orders → farmer accepts or declines → platform groups compatible orders and suggests routes → buyer confirms receipt → payment status and feedback are recorded.

## Feasibility and Viability
Start with one district and a few locally important crops selected with farmers, an FPO, and buyers. Run a small pilot before expanding. Farmers who do not regularly use apps can get help from FPO staff or local facilitators, and receive updates by SMS or voice.

The platform could earn a clearly disclosed transaction or logistics coordination fee. Price browsing and basic farmer onboarding could remain free. Test any fees with farmers and buyers before setting them.

Potential challenges and responses:
- Low adoption or limited digital skills: Offer training, assisted use, SMS updates, and screens in the main local language.
- Changing supply or produce quality: Let farmers update quantities and harvest dates, agree on grading rules, and begin with small trial orders.
- Transport delays or high costs: Start in a small delivery area, group compatible orders, confirm vehicle capacity, and allow a dispatcher to adjust routes.
- Changing prices or inaccurate forecasts: Show the source and date of price comparisons, label forecasts as estimates, and let farmers set a minimum acceptable price.
- Payment or quality disputes: Show charges before an order is accepted, issue receipts, record order changes, and provide a clear dispute process. Follow applicable market, tax, consumer, and data-protection requirements before launch.
Measure the pilot before expanding. Compare farmers’ net proceeds after transport and fees with their usual selling option. Also record buyer prices, completed orders, delivery costs, spoilage or rejection, repeat orders, and user feedback.

## Impact and Benefits
R- For farmers and FPOs: Access to more buyers, a way to compare offers, and clearer information about charges and expected payment.
- For consumers and bulk buyers: More local supply options and clearer prices.
- For logistics: Grouped orders and route planning may reduce partly filled trips, unnecessary handling, and avoidable spoilage.
- For rural communities: Local-language and assisted access can make digital selling more practical for small farms and people with limited internet access.
Track farmer net proceeds, buyer prices, on-time deliveries, transport cost per kilogram, produce rejected or spoiled, and repeat participation. Report results by crop and location to show where the service is helping and where it needs improvement.

## Research and References
e-NAM, National Agriculture Market: https://enam.gov.in/ — official information about the electronic agricultural trading platform. Its registration guidance includes information for farmers, FPOs/FPCs, traders, and logistics providers.
SFAC Farmer Producer Organization Scheme: https://sfacindia.com/fpos.aspx — official FPO scheme information and resources.
ONDC: https://ondc.org/ — information about its open-network model and the roles of sellers, buyer applications, and logistics participants.
AGMARKNET: https://www.agmarknet.gov.in/ — market price and arrivals information that may support price comparisons and forecasting, subject to data access and quality checks.
