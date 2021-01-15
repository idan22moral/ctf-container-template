# Files
Use this directory for files that should be loaded in the container.  

For example, if you need to run a Python server on your container, put the Python file here.
Example usage in the `Dockerfile` :
```Dockerfile
COPY files/server.py /home/dwight_schrute/server.py
```