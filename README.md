# citeable-docker
Instructions for creating citeable Scientific notebooks using Docker and JupyterHub

Create a public server, install latest version of docker.io from docker.com

  wget -qO- https://get.docker.com/ | sh
  
Get the latest JupyterHub container image.

  docker pull jupyter/minimal

Install a Scientific Python stack and commit the modified image.
