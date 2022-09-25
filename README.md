# sit725-2022-t2-prac9

Ensure docker desktop is installed and running

clone this repo

In the root directory of this repository, run "docker build -t sit725/prac:hd ."

After the docker command finishes, run "docker images" and get the image id of the image sit725/prac:hd

run "docker run -d -p 3000:3000 <image_id copied above>"

After this, the webapp should be available at http://localhost:3000/


Alternatively, You can run " docker run -d -p 3000:3000 akshatarora/sit725:hd"

This will download the docker image from my docker hub account and run the docker container on your machine, you can access it at http://localhost:3000/