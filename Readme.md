https://ekoparty-dast.herokuapp.com


docker run -v $(pwd):/zap/wrk/:rw -t owasp/zap2docker-weekly zap-api-scan.py -t openapi.json -f openapi -r zapreport.html -c options.prod