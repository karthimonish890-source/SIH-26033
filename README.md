# Smart India Hackathon Workshop
# Date: 13-11-2026
## Reference Number: 26012370
## Name: KARTHI M

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

1.1 Detailed explanation of the proposed solution

In the existing agricultural supply chain, farmers often depend on multiple agents and wholesalers to sell their products. This reduces the amount farmers earn while increasing the price paid by consumers.

To address this issue, we propose FarmCircle, a software-based platform that connects farmers directly with groups of consumers through a community purchasing system.

The main idea is to combine the requirements of multiple families living in the same locality into one bulk order. This allows farmers to receive larger orders instead of dealing with several small individual purchases.

The platform will include the following features:

1. Community Group Buying

Consumers from the same locality can create or join a purchasing group. They can select the vegetables and fruits they need, and the application combines their requirements into one order.

2. Advance Demand Collection

Consumers can submit their weekly requirements in advance. Farmers can view the total demand and decide whether they can supply the required quantity.

3. Direct Farmer Offers

Farmers can submit their available quantities and prices. Consumers can compare different offers before confirming their purchases.

4. Group Order Tracking

Each community can view its total order, participating members, selected products and order status through a separate dashboard.

5. Shared Delivery Planning

Orders from nearby communities can be grouped together. Existing local delivery providers or community pickup points can be used to distribute the products.

6. Transparent Price Calculation

The application displays the farmer's price, transportation expenses and service charges separately so that both farmers and consumers understand the final cost.

1.2 How it addresses the problem

FarmCircle reduces the dependency on multiple intermediaries by combining individual consumer requirements into larger orders and connecting them directly with farmers.

<img width="645" height="406" alt="image" src="https://github.com/user-attachments/assets/783c87a2-8cce-4314-9935-ac32a82dd680" />

1.3 Innovation and uniqueness of the solution

The main difference between FarmCircle and an ordinary agricultural marketplace is that it collects consumer demand first and then connects farmers with those requirements.

Its important features include:

A. Community Demand Pooling

Individual requirements from multiple families are combined into a single bulk order.

B. Demand-Based Farmer Matching

Farmers receive the actual requirements of different communities and can choose orders based on their available produce.

C. Dynamic Group Orders

Consumers can see the progress of their community order and invite other members if the required quantity has not been reached.

D. Flexible Weekly Basket

Consumers can customise their weekly vegetable baskets by adding, removing or changing product quantities.

E. Transparent Transactions

The farmer's selling price and additional expenses are displayed separately, helping both parties understand the transaction.

## Technical Approach

2.1 Technologies to be used

<img width="622" height="567" alt="image" src="https://github.com/user-attachments/assets/949e0c50-62f6-43f1-82ef-eb37f4eedb09" />

2.2 Methodology and process for implementation

1. Farmers and consumers register on the platform.

2. Consumers create or join communities based on their locality.

3. Members select the products and quantities they require.

4. The system combines individual requirements into a bulk order.

5. Total demand is displayed to registered farmers.

6. Farmers submit their available quantities and prices.

7. Consumers compare offers and confirm their orders.

8. The system calculates the final price.

9. Nearby deliveries are grouped together for distribution.

10. Order and payment records are updated after completion.

System architecture

     CONSUMERS / FAMILIES
              |
              v
      COMMUNITY CREATION
              |
              v
      PRODUCT SELECTION
              |
              v
       DEMAND POOLING
              |
              v
      TOTAL BULK ORDER
              |
              v
       FARMER DASHBOARD
              |
              v
        PRICE OFFERS
              |
              v
       ORDER CONFIRMATION
              |
              v
       DELIVERY PLANNING
              |
              v
       PRODUCT DISTRIBUTION
              |
              v
       PAYMENT RECORDS

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/18245305-36fb-44fa-a094-9e8fc8bc51a2" />
    
Working prototype modules

1. Consumer Dashboard: Register, join communities and select products.

2. Community Management: Create and manage local purchasing groups.

3. Farmer Dashboard: View requirements and submit price offers.

4. Demand Pooling: Combine individual orders into bulk orders.

5. Price Comparison: Display farmer offers and additional charges.

6. Order Management: Track orders, delivery and payment status.
   
## Feasibility and Viability

3.1 Analysis of the feasibility of the idea

Technical Feasibility

FarmCircle can be developed using commonly available web technologies. React.js, Python and PostgreSQL can handle the main application requirements. The initial demand pooling system can be implemented using basic programming logic.

Economic Feasibility

The project can initially be developed using open-source technologies and tested with a small group of farmers and consumers. Existing delivery services and collection points can be used instead of creating new infrastructure.

Operational Feasibility

Farmers and consumers can access the platform through smartphones. A simple interface with regional language support will make it easier for users who are not familiar with digital applications.

3.2 Potential challenges and risks

1. Not enough consumers may join a community order.

2. Farmers may not have the required quantity available.

3. Market prices may change before order confirmation.

4. Delivery coordination may become difficult.

5. Some users may not be familiar with online purchasing.

6. Order cancellations may affect farmers.

3.3 Strategies for overcoming these challenges

1. Allow users to invite neighbours and friends.

2. Support multiple farmers for a single order.

3. Update prices before final confirmation.

4. Use nearby community collection points.

5. Provide a simple interface with Tamil and other regional languages.

6. Introduce proper order confirmation and cancellation policies.

## Impact and Benefits

4.1 Potential impact on the target audience

The main target users of FarmCircle are:

1. Small and marginal farmers.

2. Farmer Producer Organisations.

3. Families and residential communities.

4. Vegetable and fruit retailers.

5. Restaurants and small businesses.

6. Local delivery providers.

4.2 Benefits of the solution

1. Economic Benefits

2. Better selling opportunities for farmers.

3. More competitive prices for consumers.

4. Reduced dependency on unnecessary intermediaries.

5. Lower delivery expenses through combined orders.

6. Better understanding of consumer demand.

Social Benefits

1. Encourages cooperation among local communities.

2. Connects farmers directly with consumers.

3. Creates better opportunities for small farmers.

4. Makes agricultural purchasing more transparent.

5. Environmental Benefits

6. Reduces unnecessary delivery trips.

7. Helps avoid excess purchasing.

8. Encourages local distribution.

9. Can reduce food wastage through better demand planning.

4.3 Expected outcomes

The following are proposed targets for an initial pilot:

<img width="802" height="257" alt="image" src="https://github.com/user-attachments/assets/1cda603c-e27b-4df5-b2a0-64feba48aa2e" />


## Research and References

1. National Agriculture Market (e-NAM)

https://www.enam.gov.in/

For understanding online agricultural trading and market integration.

2. Small Farmers' Agribusiness Consortium (SFAC)

https://sfacindia.com/

For information about Farmer Producer Organisations.

3. Open Network for Digital Commerce (ONDC)

https://ondc.org/

For understanding digital commerce and buyer-seller connections.

4. Ministry of Agriculture and Farmers Welfare

https://agriwelfare.gov.in/

For agricultural development programmes and government initiatives.

5. React Documentation

https://react.dev/

For frontend application development.

6. PostgreSQL Documentation

https://www.postgresql.org/docs/

For database development and management.
