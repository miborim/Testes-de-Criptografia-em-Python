# Testes de Criptografia em Python

## 👤 **Integrantes**

- [Gabriela Silva](www.linkedin.com/in/gabriela-silvaa)
- [Igor Sampaio Silva](https://www.linkedin.com/in/igor-sampaio-silva/)
- [Leonardo Nigri Griner](https://www.linkedin.com/in/leonardo-griner-477097277/)
- [Mirella Borim Lima](https://www.linkedin.com/in/mirellaborim/)

## 👨‍🏫 **Professor**

- [Victor Hayashi](https://www.linkedin.com/in/vthayashi/) - Professor de programação

## 📝 **Descrição**

&ensp; Este repositório contém a implementação e análise de SHA-256 e AES-256 em Python, utilizando diferentes bibliotecas. O objetivo é comparar o desempenho e a segurança dessas funções criptográficas por meio de 10 testes distintos, registrando os resultados em uma tabela e elaborando uma análise comparativa.

### **Bibliotecas**

&ensp; Para os testes, foram utilizadas as bibliotecas em Python:
- Hashlib;
- PyCryptodome;
- Cryptography.

### **Tabelas**

| Input | SHA-256 (Hashlib) | SHA-256 (PyCryptodome) | AES-256 (PyCryptodome) | AES-256 (Cryptography) |
|--------|------------------|------------------------|------------------------|------------------------|
| a | ca978112ca1bbdcafac231b39a23dc4da786eff8147c4e72b9807785afee48bb | ca978112ca1bbdcafac231b39a23dc4da786eff8147c4e72b9807785afee48bb | X/TWECJ8bGhXDSx6m8B8Jpz0m+SVNMqv+VGslXenF5w= | mV69RSBx91Gs5rI6t+yJhOy35Fkg2VyItAovM6DJRxc= |
| El Psy Kongroo | d048c15f016e7a3bb99759f6ea0c8c65bac9e2e811a04b4d8a6a3d0f02ce021b | d048c15f016e7a3bb99759f6ea0c8c65bac9e2e811a04b4d8a6a3d0f02ce021b | /I8Wa6fUIcc2tUIZDhcoqeUM6JBM1ZXQwl04LPGIQIg= | 16G8p8oC/2RxC5/ATbtUfKaKKkR67FUMSN7J3+a1wU0= |
| 1.048596 | d8f998989e7c76ed742659f50502b295172f764dd72517f75451c7493478b8ec | d8f998989e7c76ed742659f50502b295172f764dd72517f75451c7493478b8ec | +Y9T9BIdNnF6LanmanVceOcL5Rvb9zxMJQywluP9AXw= | CIzwcsOkYuAk2XrguYwOpmS+ohspMKhNYnful9hYYh4= |
| お前はもう死んでいる. | cb5ee74895ff1ebf77c53669037cb5528a6375dc9dc72c5628198066a59f83e1 | cb5ee74895ff1ebf77c53669037cb5528a6375dc9dc72c5628198066a59f83e1 | EWac6Hep4qj8+MU+RTQ3S5yxDjLLGlyJV5Nn3sPE5dZTjs0FbV9laHHRxhB1hrh+ | DIA8xBMqJtthsYXsz6frx3COIWoprNUtkShgL5tKAOj6GLYv/6Uw0F0vnEIjMpAN |
| Para obter algo, é preciso oferecer algo de igual valor. | 12b9298f5fdbefb4f6963f48fec0e40b5e0ee538ce3af479e5e39adec089d879 | 12b9298f5fdbefb4f6963f48fec0e40b5e0ee538ce3af479e5e39adec089d879 | QkSD7IakgF9/BPRX2Lko29xv6eEikA7ofleyjdxuEW0qNszHZRmooMcd/2ivhzCk1PxTsDbHTNJ+MNFKTbLeyOKTWAFZuDb2KNAssLygxKH5ryMLzd17F0x7CgdX/8py | YF/2yTm3hC2TZwgQJxurQyW0FHOnW0KuBfHYSNk2rxbt6ds8rQofBpn3OExkOrVAn8+z2NeXaWx3mIjm1X6pqfQTMWWywtHhwgi7kByj0DEd6iSyN+rKxy2buIrH3Ejd |
| Exemplo de teste | 378fe99acbb988f49ff6b2c67285e5a67a0baac9c135ccf4f6748c4b20b9337a | 378fe99acbb988f49ff6b2c67285e5a67a0baac9c135ccf4f6748c4b20b9337a | VOAvhD08Xy8dmt/2a3p9FJY5Nw4U7yh8ZU3bPZVz64rIh+vpuIKpWfac7jLAZToM3ueg5ylr1dWTYoIpnsqZSy57EABgZLQtA8LFmvtWaCc= | 11ymHzNk+esl8oLJCrbn5K4MgYK7N2gPVdF9Td/lXB8N7vG5Yz9+zp9QMw7SWL8503NU0Z3aNPrg4SkpcX15Z0mTsy8UPjYn4kdCV3bKOTc= |
| 3ss3 é um t3st3 b3m gr@nd3 c0m v@ri0s símb0l0s! Incluínd0 núm3r0s (1234567890), c@r@ct3r3s 3sp3ci@is (!@#$%^&*), e l3tr@s m@iúscul@s e minúscul@s. 3st@ fr@se d3v3 s3r suficient3 p@r@ um b0m t3st3 d3 c0mp@r@çã0! | a6420b4dcfa2816bf1e513b8ad066b00ee97e92d5f778faa9070a9bf93c27aaa | a6420b4dcfa2816bf1e513b8ad066b00ee97e92d5f778faa9070a9bf93c27aaa | c0epcXtdC4T9j7O8nbqlC7CHKp63rpaWyNvxIED0/Q5hvEKsMH+xQVf1OzzTuGgisySXbDdpLL1g58IGb5EH+ByjekzxmY5bSHfxgQUISeMe0gVRi7oJveKTv3ZYru87Ayfd8aJbJIAR+lcGirQMKL1QKNbJqd9nc5LQ3gb3T0Etrb8cd8oNnxCUjYykP+Qz+Jlz4bEhlQu6ltfG15W8K2dva+4kHbl8D+sHIuZAB+ZW4IE73NecAkg5tlHzGoFL53Eu1riJgC6wYfjHmvAF5VLQzM3o6SH4TOvExxRuoru0tNIdmeaD7dB2V0SZf6H7 | b9oh2ah5M7JV7PZBk1i78/38jRjqK2TXj/hS5oH4pgUFoywuVaByIWl4WO0La5I//8PIIDXwRNRFIF1H19H67jUUoVbRp/9F/xyez2laP+vzeq0i/bwCueU1/CQkY6mFkuw5/HtWcwXe0x8Uq6agAuehNRaOVBkhl9Hmaul52fY2o2ON7S3QMbrU+J+RKGQ6H6j0HWjzO8VcWOvcHShg3fI+M8wpdipU8LjXQNCqQW8N44OcC7L3AJGXtNi5vHwubRgBe6pSIW8bKWXGDInp0aOonpeYiK3LGqZ82Lx43HdhNKcC+r5HR6vxmCAdY/ZV |
| Мензажем де тесте | 9967cdd87f3ce5a73fe3d5509a5fa3b4ae7300282f1851a17157e459e5d7cdfd | 9967cdd87f3ce5a73fe3d5509a5fa3b4ae7300282f1851a17157e459e5d7cdfd | SeKrhNxS9NHivZk+xU9ceabzDaseCS2ERFeKK1s/4j1ZFioMjH69znaOuQCYBWKofmO/jZbMc25wXSSS26sEVg== | qpfj2IGe1Uh6b7AZP8iIAZay+pZnrvlGn9XvmYlV3yyzjq2rDywQfmVMpIxoLdezlGDsW4/DS5md9Pkr/J0w0A== |
| Μήνυμα δοκιμής | dd5592ac7d572bbd5b63bfd0126a99ad438e194d7d2d5ffc4e0f8e20cd013152 | dd5592ac7d572bbd5b63bfd0126a99ad438e194d7d2d5ffc4e0f8e20cd013152 | 7zzaYDQyYJyu2kONEdHw83W4tZJzfucvNjNX46iADfdakSmrjJlOvs3IxyLLL1+N | +qjyDjBft8UbacIjkGUYCPCMaQxlJklNwNH6rjYegt0JD33NccUfXiikB8dX1hqw |
