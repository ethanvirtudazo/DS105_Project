# DS105_Project

LSE Career Hubbers Github Page

GitHub Pages Access: https://torreshong.github.io/

## Objective

For our DS105 Project, our group decided to use data from the LSE Career Hub (LSE's internal career website for students) to create a dashboard to help students in their applications for specific industries. The dashboard displays the distribution of in-demand skills, the seasonal application peaks, the proportion of work for undergraduate and postgraduate students, and the location of the job. Through web scraping, we extracted key information for every job opportunities under "investment banking" from 2012 to 2022, ending up with more than 6600 job postings. The dataset contained a mixture of unstructured and structured data. Namely, the skills required by employers was embedded in instructured text data that varied across job postings. As such, natural language processing was leveraged to identify relevant keywords.

## Replicating the project
In order to replicate the project and final results, the necessary files are: 6622_jobs.xls (the primary dataset), data_viz_company.ipynb, data_viz_dates.ipynb, data_viz_job_types.ipynb, and text_pipeline.ipynb.

## Issues:
The data colleection script (data_collection.ipynb) may not work exactly the same way as the first time we extracted the initial 6623 as the website navigate may slightly vary over time.
