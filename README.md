# docker---Apache-PHP-MySQL-phpMyAdmin
- Menjalankan semua services container:
  ```
  docker-compose up -d
  ```
- Menjalankan container yang sudah ada dan pernah dibuat:
  ```
  docker-compose start
  ```
- Stop dan hapus container, tapi data volume tetap ada:
  ```
  docker-compose down
  ```
- Stop sementara tanpa menghapus container:
  ```
  docker-compose stop
  ```
- lihat container yang sedang berjalan:
  ```
  docker ps
  ```
- Menjalankan termial MySQL di container Docker
  ```
  docker exec -it your_container_id mysql -u root -p
  ```
----------------

author:
--
<p align="center" >
  <a href="https://github.com/yuriya-dev" target="_blank">
    <img src="https://i.postimg.cc/F16xhxs4/avatar.png" alt="My Avatar" width="32" />
  </a>
  | yuriya-dev
</p>
