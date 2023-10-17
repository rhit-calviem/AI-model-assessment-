# AI-model-assessment
1) Given the data set, do a quick exploratory data analysis to get a feel for the distributions and biases of the data.  Report any visualizations and findings used and suggest any other impactful business use cases for that data.
 
   The exploratory data analysis of the dataset reveals important information. The data shows that there is a majority of Year 2 and 3 students. There is a big pool of majors, but Biology and Physics are the most common. Orders are university-specific, which could potentially introduce a bias favoring universities with more participation. Furthermore, the dataset highlights that most orders are placed during lunch (11-15 timeframe); this is to be expected at college campuses as almost all students will be on campus during this time. Additionally, other biases outside of the university bias could be:
   - lack of demographic information, could lead to underrepresentation or misrepresentation.
   - seasonal changes, orders might change seasonally, affecting model accuracy.
  
The dataset could have valuable applications in other businesses such as:
   - Supply Chain Optimization, determining the demand for specific items across universities would create a better inventory management.
   - Marketing Strategies, tailoring marketing campaigns to specific universities or majors based on food preferences.
   - Operational Efficiency, optimizing staff schedules and cooking processes based on peak order times and preferences.

2) Consider implications of data collection, storage, and data biases you would consider relevant here considering Data Ethics, Business Outcomes, and Technical Implications
      Discuss Ethical implications of these factors
      Discuss Business outcome implications of these factors
      Discuss Technical implications of these factors
   
      Ethical considerations play a big role in data collection and in addressing potential biases. It's extremely important to address privacy concerns and obtain consent. There should be a strong emphasis on data anonymization and compliance with regulations to prevent privacy violations (a good example is that data provided in this assessment as there is no specifics on the students, but just year, major and univeristy). Avoiding biases in the data, particularly those regarding majors and universities, is essential to ensure fairness in predicting orders. Accountability in the algorithms used for these predictions is necessary, especially since students receive discounts when predictions are incorrect. All of these ethical practices are key in building customer trust and satisfaction. From a business perspective, there is the potential for an improved brand reputation, which could lead to major succes in the future. On the technical side, ensuring data quality, model fairness, and secure data storage is vital to achieving accurate predictions, data security, and the ability to manage growing data volumes as the business expands.
Striking a balance between these ethical, business, and technical considerations is essential for responsible data utilization and mantaining and growing the company.

3) Given the work required to bring a solution like this to maturity and its performance, what considerations would you make to determine if this is a suitable course of action?
   
   When considering the idea of implementing an AI-powered system, there are several key factors that demand evaluation. Firstly, the quality and quantity of the available data need to be assessed. Furthermore, it is important to ensure that data usage aligns with ethical and privacy standards. It is also essential to establish clear performance metrics and understand what level of accuracy is needed for the business. The potential costs, in terms of development, data procurement, and maintenance, should be weighed against the expected benefits. Additionally, the long-term sustainability and adaptability of the AI system in response to changing customer preferences (such as seasononal changes) are important for making informed decisions. Finally, strategies to mitigate the risks caused by incorrect predictions, including the mentioned 10% discount, should be thought out to ensure the company's success.
   
