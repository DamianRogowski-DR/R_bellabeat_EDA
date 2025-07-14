# Buisness Task and relevent questions: 

When starting the analysis, it is only natural to define what we are looking for, depending on the business task set by our stakeholders. In this case, we have been asked to analyse smart device usage data to find out how customers use competitors' devices. Then, based on the key findings that we will present, we need to select the products that will be developed. 

Let's break down the main question:

1. What are some trends in smart device usage?

  - How are users presenting themselves in terms of physical activities?
  - What anomalies are there in the data?
  - What kind of struggles or unhealthy behavior do users exhibit?
  - What part of their active life needs to be corrected or changed?
  
2. How could these trends apply to Bellabeat customers?

  - What features can we add to existing products to help our users?
  - How can we change users' view of and perception of daily activities?
  - How can we incorporate the device into people's lives?
  
3. How could these trends influence the Bellabeat marketing strategy?

  - Presenting solutions that help users become the best versions of themselves.
  - Promoting certain behaviors in a light and approachable way.
  - Focus on aspects of assisting users.

# Analysis proceses:

My analysis is structured within two primary R notebooks:

process_cleaning_merging.Rmd [link]: This notebook meticulously outlines my approach to data cleaning and preprocessing. It demonstrates my ability to transform data into a clean, usable format ready for analysis.

analysis_visualization.Rmd [link]: Here, you'll find a comprehensive journey through my exploratory data analysis. This notebook showcases my critical thinking and ability to extract actionable insights from data.

These notebooks aren't just code; they represent my end-to-end data science process, from initial data understanding to final conclusions. They're designed to give you a clear picture of how I think and operate as a data professional.

# Summary:

### Observed trends in data:

Analysis of smart device data reveals several significant trends in user behavior related to physical activity and sleep. On average, users exhibit a low daily step count, averaging 7,638 steps, which falls short of the recommended 10,000 steps for optimal health benefits. The majority of their physical activity is categorized as light exertion, suggesting a lack of sustained, moderate-to-vigorous exercise. Peak activity periods are observed between 8 AM and 7 PM, with noticeable increases during lunchtime (12 PM - 2 PM) and in the evenings (5 PM - 7 PM), aligning with commutes and daily errands. The 5-7 PM window also appears to be a preferred time for more focused exercise.

A concerning anomaly in the data is an unusually high average Metabolic Equivalent of Task (MET) value of 15 METs per minute, which raises questions about the accuracy of the device's measurement methodology. This discrepancy needs to be addressed to ensure data integrity and user trust.

Regarding sleep patterns, users frequently experience sleep onset insomnia, taking around 30 minutes to fall asleep. Their sleep schedules are irregular, and there's a noticeable weekday sleep deprivation pattern, where users sleep less on Mondays and Tuesdays, compensating on Wednesdays, leading to overall inconsistent rest. Actual sleep time rarely exceeds 7.5 hours, and a significant difference exists between time spent in bed and actual sleep minutes.

These observations highlight user struggles with insufficient exercise, inefficient activity patterns, and poor sleep hygiene, all of which need correction to foster healthier lifestyles.

### Insights application

These trends offer valuable insights for enhancing Bellabeat's product offerings. To address the low activity levels, Bellabeat can introduce personalized step goals and exertion prompts to encourage users to increase their activity intensity. Real-time feedback advising users on tempo and stride, coupled with efficient exercise tips for boosting activity scores, would be highly beneficial. Implementing gamification features like pre-calculated goals and achievement badges could significantly motivate users.

For sleep improvement, features such as customizable sleep schedules, pre-sleep reminders (e.g., an hour before bedtime to avoid phone use), and relaxation techniques within the app would help users establish healthier sleep habits.

Crucially, Bellabeat must prioritize data accuracy and transparency. This includes consistent measurement validation, prompting users for device inspection if abnormal results persist, and clearly stating measurement methodologies in device instructions, especially concerning the high MET values.

Bellabeat can influence users' perception of daily activities by emphasising incremental progress and making higher exertion levels more accessible. Promoting holistic well-being by connecting activity and sleep to overall health will reinforce the value proposition. Integrating the device into daily life can be achieved through contextual reminders during peak activity times and transforming raw data into actionable, personalized recommendations.

### Marketing strategy based on key findings: 

These insights can refine Bellabeat's marketing approach. The strategy should focus on empowerment, positioning Bellabeat as a tool that helps users take control of their health through actionable insights. Marketing should highlight "Achievable Health," showcasing how Bellabeat helps users integrate healthy habits seamlessly into their lives, making health goals less daunting.

Promoting healthy behaviors should be done in a light and approachable way. Campaigns can leverage gamified challenges to highlight the fun and rewarding aspects of health goals.

Finally, the marketing strategy should focus on assisting users, positioning Bellabeat as a "Personal Health Coach" that provides guidance, reminders, and motivation. Emphasizing proactive features that go "Beyond Tracking" will differentiate Bellabeat in the market, and transparent communication regarding data accuracy will build trust.
