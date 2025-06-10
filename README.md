# docker---Apache-PHP-MySQL-phpMyAdmin
- Menjalankan pertama kali:
  ```
  docker-compose up -d
  ```
- Menjalankan docker
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
- Menjalankan MySQL di container Docker
  ```
  docker exec -it your_container_id mysql -u root -p
  ```
----------------
