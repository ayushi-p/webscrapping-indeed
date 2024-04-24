# Webscrapping-Indeed.com
The purpose of this project is to design a course curriculum for a new “Master of Business and Management in Data Science and Artificial Intelligence” program at University of Toronto with focus not only on technical but also on business and soft skills. To achieve this goal, we had to extract skills that are in demand at the job market from job vacancies posted on indeed web-portal and apply clustering algorithms to group/segment skills into courses.

Part 1 consists of utililizing the geckodriver extension for Arsenic on Python to set up the webscraping process. It consists of the following general steps:
1. Checking whether the website allows web scraping
2. Obtaining the source code (HTML File) by using the website URL
3. Downloading the website content
4. Parsing the content using keywords tags for elements of interest
5. Extracting relevant data/features
6. Organizing raw data in structured format (e.g., CSV)

Part 2 then includes EDA and Feature Engineering, following which unsupervised machine learning methods such as Hierarchal Clustering and K-Means are implemented to perform grouping. Then the results are collated and domain-specific evidence-based insights are provided.
