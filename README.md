# Introduction
Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Sršen used her background as an artist to develop beautifully designed technology that informs and inspires women around the world. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women. The five(5) products produced by Bellabeat are :

- Bellabeat app: The Bellabeat app provides users with health data related to their activity, sleep, stress, menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and make healthy decisions. The Bellabeat app connects to their line of smart wellness products.
- Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects to the Bellabeat app to track activity, sleep, and stress.
- Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your daily wellness.
- Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your hydration levels.
- Bellabeat membership: Bellabeat also offers a subscription-based membership program for users. Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and beauty, and mindfulness based on their lifestyle and goals.
This dataset has been originally generated by respondents to a distributed survey via Amazon Mechanical Turk and contains personal fitnesss tracker of thirty(30) eligible fitbit users. The dataset used for the purpose of this analysis is available on Kaggle (FitBit Fitness Tracker Data | Kaggle)[https://www.kaggle.com/datasets/arashnic/fitbit].

I will be working in the capacity of a junior data analyst to identify key business tasks following the six(6) data analysis procedures namely : Ask, Prepare, Process, Analyze, Share, Act.

Ask Phase
The key business task of this analysis is to analyze smart device usage data in order to gain insight into how consumers use the non-Bellabeat smart devices which would subsequently, help influence Bellabeat marketing strategy. The key stakeholders for this project are as identified below;

Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer.
Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team.
Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy.
Prepare Phase
The prepare step generally provides adequate information on data source.

The dataset used for this analysis is publicly available on Kaggle -FitBit Fitness Tracker Data | Kaggle , and is stored in eighteen(18) csv. files which consists of daily activities such as; steps, calories, heartrate, sleep, etc.
The data, which contains personal tracker was submitted and consented to by 30 eligible fitbit users.
Most of the csv. files are stored in long format while some are stored in narrow format.
To test the integrity of the data; the dataset is expected to be ROCCC which stands for Reliable, Original, Comprehensive, Current , Cited respectively.
Reliable- the reliability of the dataset can be contested as there are some limitations. For instance, the sample size,(personal tracker details of only 30 users was provided) which may lead to sampling bias. Similarly, the gender of the 30 users is completely unknown and it is a fact that Bellabeat as a wellness company is majorly focused on the wellness and fitness of women.
Original- the dataset cannot be said to be original as it was provided by a third party(Amazon Mechanical Turk)
Comprehensive- the dataset can be said to be comprehensive enough as the whole of the 18 csv files contains adequate information about the users’ activity ranging from heartrate, sleeptime, intensities, calories burnt, weight etc.
Current- For a dataset that was collected and last updated since 2016, and is being used for an analysis in 2022, the dataset cannot be said to be current.
Cited- the dataset has been properly cited as a third party data and is available in the public domain.
5. The dailyActivity_merged , weightLoginfo_merged and sleepDay_merged csv files have been selected to carry out this analysis as the former contains all tracker details of users on a daily basis. All 3 files were migrated into one workbook but different sheets and saved as an excel workbook.
