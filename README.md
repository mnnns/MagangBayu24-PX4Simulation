# Magang Bayucaraka 2024 - PX4 Simulation

Nama    : Naswan Nashir Ramadhan\
NRP     : 5025231246

## Cara Pengumpulan
- Fork repositori ini
- Buat workspace
  ```sh
  mkdir -p {nama-workspace}/src
  ```
- Pergi ke ```{nama-workspace}/src```
  ```sh
  cd {nama-workspace}/src
  ```
- Clone repositori
- Buat 1 package yang berisi 3 node control drone \
  **CPP**
  ```sh
  ros2 pkg create --build-type ament_cmake {nama-package}
  ```
  **Python**
  ```sh
  ros2 pkg create --build-type ament_python {nama-package}
  ```
- Sertakan dokumentasi untuk setiap tugas yang berisi **laporan singkat** mengenai langkah pengerjaan, kendala saat mengerjakan, bagaimana caramu menyelesaikan masalah tersebut, dan **link video simulasi**. Dokumentasi dikumpulkan dalam bentuk PDF dengan format ```{nama}.pdf```. Dokumentasi 3 penugasan diletakkan di dalam folder ```docs```.

