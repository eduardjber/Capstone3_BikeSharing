# Capstone3_BikeSharing

Bike Sharing merupakan evolusi modern dari system penyewaan sepeda tradisional, di mana seluruh proses—mulai dari keanggotaan, penyewaan, hingga pengembalian—telah sepenuhnya otomatis. Sistem ini memungkinkan pengguna untuk menyewa sepeda dari satu lokasi dan mengembalikannya di lokasi lain dengan mudah. Saat ini, terdapat lebih dari 500 program bike-sharing yang beroperasi di seluruh dunia, dengan jumlah sepeda melebihi 500.000 unit. Sistem ini semakin menarik perhatian karena peran pentingnya dalam mengatasi kemacetan lalu lintas, menjaga kelestarian lingkungan, dan meningkatkan kesehatan masyarakat.

dteday: date
season: season (1: winter, 2: spring, 3: summer, 4: fall)
hr: hour (0 to 23)
holiday: holiday or not
temp: normalized temperature in Celsius. The values are derived via (t-tmin)/(tmax-tmin), tmin=-8, t_max=+39 (only in hourly scale)
atemp: Normalized feeling temperature in Celsius. The values are derived via (t-tmin)/(tmax-tmin), tmin=-16, t_max=+50 (only in hourly scale)
hum: normalized humidity. The values are divided into 100 (max)
casual: count of casual users
registered: count of registered users
cnt: count of total rental bikes including both casual and registered
weathersit:
1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog


CONCLUSION
Model XGBoost berhasil memprediksi jumlah penyewa sepeda dengan akurasi baik dengan melakukan Hyperparameter Tuning

Nilai RMSE yang rendah menunjukkan error prediksi yang kecil terhadap data actual

MAPE menunjukan nilai 44% sehingga model ini bisa diperkirakan ada meleset sekitar 44%

Model juga cukup fleksibel untuk menangkap pola musiman dan jam sibuk



RECOMMENDATION
Model ini bisa digunakan untuk penggunakan di hari-hari tertentu

Dapat dikembangkan lebih lanjut dengan memasukkan data cuaca aktual atau data lalu lintas

Next Improvement untuk dapat diintegrasikan dengan data real time agar model bisa semakin akurat




