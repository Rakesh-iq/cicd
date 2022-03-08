# buildspec.yml 
Create S3 Bucket to store CFT Templates

# main.yml 
Modify TemplateURL with s3 bucket (above created)

main.yml will create S3 Bucket for Dags :
DEV: dev-airflow-store-dags