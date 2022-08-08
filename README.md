##INSTALASI
git clone https://github.com/nalonal/cuaca<br>
cd cuaca<br>
chmod u+x install.sh<br>
./install.sh

##PEMAKAIAN SETIAP HABIS STOP ENGINE
sudo chmod 666 /var/run/docker.sock

##Terminate
docker system prune<br>
docker compose down --rmi all -v --remove-orphans<br>
rm -r cuaca