*** ELK Stack Basic Project 

- Set Up Docker Environment
  - Create a Docker Compose File
  - Create Logstash Pipeline Configuration
- Start the ELK Stack
  - Run Docker Compose
- Prepare Sample Log Data
  - Create a Sample Log File
  - Update Logstash Pipeline Configuration
  - Copy the Sample Log File
    -     docker cp sample.log logstash:<your_path_to_sample_log_file>/sample.log
- Verify Logstash Configuration
  - Restart Logstash
    -     docker-compose restart logstash
  - Check Logstash Logs
    -     docker logs -f logstash
- Access Kibana
  - Open Kibana:
    -     http://localhost:5601
  - Configure Index Pattern
- Visualize the Logs
  - Discover Logs
  - Create Visualizations

![image](https://github.com/user-attachments/assets/afa8fddf-7eed-4508-8415-7fda71a9e523)

![image](https://github.com/user-attachments/assets/e3141bb1-eda9-4f20-90fe-4be5138037b7)

![image](https://github.com/user-attachments/assets/b02db593-8cf2-4bb4-a3b3-eeb78fed8cae)

![image](https://github.com/user-attachments/assets/80c834f0-96c0-40e5-8582-5a0470734761)
