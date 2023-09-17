# Reduce CO2 Emissions

## Introduction
The delicate balance of greenhouse gases has played a crucial role in maintaining a livable climate for humans and the diverse array of species that inhabit our planet. However, this equilibrium has been disrupted, posing a significant threat to the survival and distribution of life on Earth. The concentration of carbon dioxide, the most abundant and dangerous greenhouse gas, has reached unprecedented levels in our atmosphere. This alarming increase is primarily attributed to human activities, particularly the burning of fossil fuels. As these gases are released into the air, they absorb solar energy and trap heat near the Earth’s surface, a phenomenon known as the greenhouse effect. This heightened greenhouse effect has far-reaching implications. It hinders the natural dissipation of heat into space, leading to rising temperatures and climate disruptions. These changes in our climate system have the potential to reshape the distribution of habitats and alter the conditions necessary for various organisms to thrive.

By recognizing the urgency of this situation, we can strive to restore the delicate balance of greenhouse gases and mitigate the impacts of climate change. Implementing sustainable practices, transitioning
to renewable energy sources, improving energy efficiency, and adopting environmentally conscious lifestyles are all crucial steps in reducing greenhouse gas emissions and especially the CO2 emission,
to ensure a healthier, more resilient environment for generations to come. I decided to undertake a project on CO2 emissions due to my deep love and concern for the environment. As an eco-friendly
individual, I am passionate about preserving the natural world and its precious resources. My affection for animals further motivates me to take action against climate change and reduce my carbon footprint. I actively strive to make sustainable choices in my daily life, such as recycling waste, limiting the amount of water I am using and minimizing air travel whenever possible by taking the train, as I
understand the significant impact it has on CO2 emissions. By delving into the topic of CO2 emissions, I aim to gain a deeper understanding of the issue and contribute to finding effective solutions that can
mitigate the environmental challenges we face.

## Data Modeling and Preparation
###  Conceptual Entity-Relationship and Logical Snowflake schema
After constructing the ER schema using JMerise, the logical snowflake schema was derived from the conversion of the MCD file, as illustrated in this figure. More details in the report.

### Data Preparation
Upon examining the three datasets, I determined the time periods covered by each of them. The first dataset, ”CO2 and Greenhouse Gas Emissions,” spans from 1750 to 2021, providing a comprehensive historical perspective. The second dataset, ”Extreme Poverty,” covers the years from 1981 to 2021,
offering a more recent focus on poverty-related data. Lastly, the dataset titled ”CO2 emissions of all world countries” encompasses the years from 1970 to 2021, providing a broader range of information
on CO2 emissions. To ensure a meaningful intersection among the datasets and minimize the presence of missing values, I made the decision to retain only the observations from 1981 to 2021. This
narrower time frame allows for a consistent and aligned analysis across the datasets, enabling effective comparison and exploration of the data. With the data aligned in terms of time period, I proceeded
to analyze each dataset individually. Extensive details about each source of data are mentioned in the report, The full code is here Data Preparation Code.ipynb.