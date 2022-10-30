# Working with the NiFi REST API
This video will get you started working with the NiFi Rest API 1.18.0

### Requirements
- WSL 2
- Ubuntu 22.04 distro
- Docker Desktop
- VS Code


### VS Code Extensions
- Local
    - [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
- WSL:Ubuntu-20.04
    - [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) 
    - [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)

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
