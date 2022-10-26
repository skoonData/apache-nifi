# Working with the NiFi REST API(work in progress)
This video will cover the basic of working with the NiFi REST API.

### Requirements
- Docker Desktop
- Visual Studio Code

### VS Code Extensions
- Docker
- Remote Development
- Thunder Client

### Environment Setup
 1. Clone the repo.

 2. Create "nifi" docker network.
    ```bash
        docker network create nifi
    ```
 3. Run the NiFi container.
    
    ```bash
        docker compose up -d
    ```

 4. Use the username and password from docker-compose.yml to access the NiFi UI.

 5. Watch the video.
 
 6. When your done you can use this command to remove the container and volumes that are were created.
    ```bash
        docker compose down -v
    ```


### Links
- [Apache NiFi Docs](https://nifi.apache.org/docs.html)