# JupyterLab

Supercharging AI/ML Development with JupyterLab and Docker

JupyterLab is an open source application built around the concept of a computational notebook document. It enables sharing and executing code, data processing, visualization, and offers a range of interactive features for creating graphs.

https://www.docker.com/blog/supercharging-ai-ml-development-with-jupyterlab-and-docker/



# Colaboratory

Local runtimes
Colab lets you connect to a local runtime. This allows you to execute code on your local hardware.

https://research.google.com/colaboratory/local-runtimes.html

```
 ssh -L [local_port]:[destination_address]:[destination_port] [username]@[ssh_server]
 ssh -L 8888:localhost:9999 tower



 ssh -L 8000:localhost:9000 tower


 docker-compose exec jupyter bash -c 'jupyter server list'

```
