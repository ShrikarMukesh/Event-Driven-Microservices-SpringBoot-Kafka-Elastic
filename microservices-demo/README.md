# Running the application
- Please enter the correct credentials in twitter4j.properties file.
- Then run TwitterToKafkaServiceApplication inside IntelliJ, or run with mvn spring-boot:run command
- To use the mock tweets, set enable-mock-tweets: true in application.yml file
- Observe that we moved the TwitterToKafkaServiceConfigData to a new module called app-config-data
- 
- Question 1:Which of the below options will increase the throughput on a kafka producer? Select all that apply.
   a.) Increasing batch size
   b.) Decreasing linger-ms 
   c.) Setting a compression type such as snappy 
   d.) Increasing linger-ms 
- ANS is a , c, d

