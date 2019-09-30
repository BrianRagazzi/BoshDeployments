To Deploy:

bosh -e pae deploy -d minio minio-lab-tls.yml \
    -l minio-tls.yml \
    -v minio_deployment_name=minio \
    -v minio_accesskey=MYACCESSKEY \
    -v minio_secretkey=MYSECRETKEY


* pae is the BOSH environment
* MYACCESSKEY and MYSECRETKEY are example credentials
