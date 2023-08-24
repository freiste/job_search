# job_search
This script scrapes different Swiss job-search-websites (jobs.ch, data-jobs.ch, ostjob.ch) for job-titles which match a definable pattern (eg. 'data analyst'). 

The newly found jobs are compared to the job-masterlist. All new jobs which are not allready stored in the masterlist, will be stored in a new excel-file 'new_jobs.xlsx'. 

The following job-informations are stored in the excel-file: 'job_name',	'job_plz',	'job_location',	'job_company',	'job_link',	'job_date'.

