# graylog:5.2
### To install graylog:  
- Please clone repository and set variables in `.env` file
- Enter the following command:
  ```bash
  docker compose up -d
  ```
- After that enter the following commands:  
  ```bash
  cd docker
  sudo chmod -R 777 graylog_data
  chmod -R 777 opensearch-data
  chown -R 1100:1100 graylog_journal
  ```

