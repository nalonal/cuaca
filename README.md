## INSTALASI
git clone https://github.com/nalonal/cuaca<br>
cd cuaca<br>
chmod u+x install.sh<br>
./install.sh

## STARTING
docker compose up -d

## PEMAKAIAN SETIAP HABIS STOP ENGINE
sudo chmod 666 /var/run/docker.sock<br>
cd cuaca<br>
docker compose up -d<br>

## Terminate
docker system prune<br>
docker compose down --rmi all -v --remove-orphans<br>
rm -r cuaca <br>