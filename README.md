# shell2024
Decarbonizing fleet.

Introduction -

Welcome to the fifth edition of the Shell.ai Hackathon for Sustainable and Affordable Energy. Shell.ai Hackathon brings together brilliant minds passionate about digital solutions and AI, to tackle real energy challenges and help build a lower-carbon world where everyone can access and afford energy.In the previous four editions, we addressed some of the digital challenges around the energy transition: windfarm layout optimization (2020), irradiance forecasting for solar power generation (2021), optimal placement of electric vehicle (EV) charging stations (2022), and supply chain optimization for biorefineries (2023). This year, we focus on fleet decarbonization - a transition problem in the mobility sector.

Challenge -

Professional, delivery and operational fleets are a significant contributor to global greenhouse emissions. Fleet owners aspire to achieve net-zero emissions promptly; however, the transition presents a complex dilemma. Balancing the urgency of achieving net-zero emissions with business sustainability and customer satisfaction requires a decision-making framework that considers factors such as timing,location, and approach. In this hackathon, you will have a chance to develop mathematical models to optimize fleet decarbonization strategies, to help fleet owners make informed decisions that align with their energy transition objectives and business outcomes. By harnessing the power of data and mathematical models, you will navigate the complexities of demand forecasts, dissect emission profiles,and find ways to meet ambitious emission targets. The end game is to develop ingenious solutions that strike a balance between operational effectiveness and environmental impact.

Problem Statement -

Road transport is the backbone of supply chain, playing a pivotal role in moving goods and bolstering the economy. This mode of transport’s advantages are flexibility, door-to-door service, and connectivity between cities, towns, and villages. While it comes with convenience and advantage, professional, delivery and operational fleets are a significant contributor to global greenhouse emissions. Fleet owners aspire to achieve net-zero emissions promptly; however, the transition presents a complex dilemma. Balancing the urgency of achieving net-zero emissions with business sustainability and customer satisfaction requires a decision-making framework that considers factors such as timing, location, and approach. In this hackathon, you will have a chance to develop mathematical models to optimize fleet decarbonization strategies, to help fleet owners make informed decisions that align with their energy transition objectives and business outcomes. By harnessing the power of data and mathematical models, you will navigate the complexities of demand forecasts, dissect emission profiles, and find ways to meet ambitious emission targets. The end game is todevelop ingenious solutions that strike a balance between operational effectiveness and environmental impact.We will provide various yearly ‘demand’ data from a fleet operator that must be met. The demand data is further divided into various size and distance buckets which indicate what vehicle sizes should be used and how much distance per day they can cover. These are some additional constraints imposed on meeting the customer demand. We provide various vehicles from the following 3 drivetrains: Diesel, LNG, and BEV (Battery Electric Vehicle). For each of these vehicles, the cost, operational yearly range, distance bucket they can cover, and the vehicle ID (unique identifier which helps you reference them in your solution) is provided. We include the information on the fuel consumption by every model of the vehicle and the corresponding fuel types. Furthermore, we also include the cost for every fuel type along with the amount of carbon emissions by each of them, for every single year. Finally, you are also provided with the total carbon emission limits that must not be exceeded every year. All the data provided spans the years 2023 to 2038 (both years inclusive), for a total of 16 years

Your solution should provide an optimal fleet composition over the years, which meets all supply-chain demand and constraints while abiding by the carbon emission limits for every year and has the lowest overall cost possible. The data provided to you and the solution expected from you has been further explained in the next section.
