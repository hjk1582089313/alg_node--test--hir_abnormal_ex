# xxl-job-executor-sample-springboot
xxl-job-executor-sample-springboot docker with python
打包镜像
生成python环境

git pull
docker build -t kobedocker24/xxl-job-executor-sample-springboot:2.2.0 .
docker push kobedocker24/xxl-job-executor-sample-springboot:2.2.0

  docker run -p 8081:8081 -p 9999:9999 -v /root/xxl-job-executor-sample-springboot/application.properties:/application.properties --name xxl-job-executor-sample-springboot  -d kobedocker24/xxl-job-executor-sample-springboot:2.2.0
