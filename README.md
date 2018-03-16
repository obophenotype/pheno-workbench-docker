To install:

`docker pull matentzn/pheno-workbench-docker`

Run in background:

`docker run -i -t -d -p 8080:8080 matentzn/pheno-workbench-docker`

Access app:

`http://localhost:8080/browser-0.0.1/` in web browser (Chrome, Firefox, Edge, Opera)

Stop:

Check container id with `docker ps`, then `docker stop CONTAINERID`
