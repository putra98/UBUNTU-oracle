# UBUNTU-oracle
Menginstall oracle dengan docker 
Pastikan docker sudah terinstall.

Download oracle

```docker pull thebookpeople/oracle-xe-11g```

Membuat usermod 

```sudo usermod -aGdocker ${USER}```

Menjalankan images

```docker run thebookpeople/oracle-xe-11g```

Mengecek container yang berjalan

```docker ps -a```

Menjalankan container/id container

```docker start f8a78f3a2b04```

Menjalankan container id ke mesin.

```docker exec -it f8a78f3a2b04 /bin/bash```

Masuk oracle system

```sqlplus```

Masuk username system

```username = system```

```password = oracle```
