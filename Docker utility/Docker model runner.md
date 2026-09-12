# Docker model runner  
- Install Docker desktop.
- Go to the bottom of the docker desktop and ensure the version is latest.
- Take your terminal and run
  ~~~
  docker model -h
  ~~~
- You can download different docker models from https://hub.docker.com/r/ai/
- Select the desired one
- Copy the model name and run
~~~
docker model pull modelname
docker model run modelname
~~~
Interactive mode:
~~~
docker model run modelname  
~~~
- and click on enter it will open an interactive session
- 
