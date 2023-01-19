# gtech
Repository for Georgia Tech's code development assignments

Get image from docker repo

```
docker pull jupyter/r-notebook
```

Run image with your local folder

```
docker run -p 8888:8888 --name notebook {YOUR_LOCAL_FOLDER}:/home/jovyan/work -e JUPYTER_ENABLE_LAB=yes -it jupyter/r-notebook
```

Access your image with the url at the end of the docker run command (please use WSL or Terminal)

Put both files from this repo at /work forlder 

HW1 Header SP22.ipynb
credit_card_data-headers.txt

Otherwise you can just view the results here in gitlab

Thanks, any question

karto@gatech.edu