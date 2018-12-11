##**_Basic commands book_**

## Tmux

| **Command**                             | **Notes**                                                                |
| --------------------------------------- | -------------------------------------------------------------------------| 
| **tmux ls**                             | List all sessions	                                                     | 
| **tmux new -s "name"**                  | New session with name                                                    | 
| **tmux attach -t name**                 | Attach session by name                                                   |
| **tmux rename-session -t 0 newname**    | Rename session                                                           | 
| **tmux detach**                         | The mount point for certs, keys to be injected to the container          | 

## Terminator

| **Command**                   | **Notes**                                                                          |
| ------------------------------| -----------------------------------------------------------------------------------|
| **ctrl+shift+t**              | New tab	                                                                         |
| **shift+ctrl+w**              | Close tab                                                                          |
| **shift+ctrl+o**              | Split horizontal tab                                                               |
| **shift+ctrl+e**              | Split vertical tab                                                                 |

## Docker

| **Command**                                       | **Notes**                                                                          |
| --------------------------------------------------| -----------------------------------------------------------------------------------|
| **docker system prune**                           | This will remove:stopped containers,networks not used,dangling images,build cache  |                                                                                                                                                                      |
| **docker system prune -a**                        | This will remove:stopped containers and all unused images                          |
| **docker rmi $(docker images -a -q)**             | This will remove:all images                                                        |
| **docker rm $(docker ps -a -f status=exited -q)** | This will remove:all containers                                                    |
| **docker stop $(docker ps -a -q)**                | This will stop  :all containers                                                    |
| **docker docker rm $(docker ps -a -q)**           | This will remove:all containers                                                    |
| **docker volume**                                 | Docker volumes                                                                     |
| **docker rm -v container_name**                   | This will remove:container with volume                                             |





## Linux

| **Command**                   | **Notes**                                                                          |
| -------------------------     | -----------------------------------------------------------------------------------|
    
