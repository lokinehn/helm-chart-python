Simple helm chart for python web application with celery worker and non persistent redis pod.

Pod with web server also created with two init containers: first one is for running test, second one is for running migrations to DB.
