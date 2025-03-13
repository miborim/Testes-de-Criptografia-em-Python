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

| Input | SHA-256 (Hashlib) | SHA-256 (PyCryptodome) | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
|--------|--------------|------------|--------------------|-------------------|-------------|------------|
| a |ca978112ca1bbdcafac231b39a23dc4da786eff8147c4e72b9807785afee48bb | ca978112ca1bbdcafac231b39a23dc4da786eff8147c4e72b9807785afee48bb | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) |  AES-256 (Cryptography) |  AES-256 Decrypted (Cryptography)|
| El Psy Kongroo | d048c15f016e7a3bb99759f6ea0c8c65bac9e2e811a04b4d8a6a3d0f02ce021b | d048c15f016e7a3bb99759f6ea0c8c65bac9e2e811a04b4d8a6a3d0f02ce021b | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
| 1.048596 | d8f998989e7c76ed742659f50502b295172f764dd72517f75451c7493478b8ec | d8f998989e7c76ed742659f50502b295172f764dd72517f75451c7493478b8ec | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
| お前はもう死んでいる. | cb5ee74895ff1ebf77c53669037cb5528a6375dc9dc72c5628198066a59f83e1 | cb5ee74895ff1ebf77c53669037cb5528a6375dc9dc72c5628198066a59f83e1 | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
| Para obter algo, é preciso oferecer algo de igual valor. | 12b9298f5fdbefb4f6963f48fec0e40b5e0ee538ce3af479e5e39adec089d879 | 12b9298f5fdbefb4f6963f48fec0e40b5e0ee538ce3af479e5e39adec089d879 | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
| Exemplo de teste | 378fe99acbb988f49ff6b2c67285e5a67a0baac9c135ccf4f6748c4b20b9337a | 378fe99acbb988f49ff6b2c67285e5a67a0baac9c135ccf4f6748c4b20b9337a | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
| 3ss3 t3st3 contém vári0s símb0l0s dif3r3nt3s! | 8826cbf76bbac56dc9c5391c6cf8b663a82a4bca14409d237eec2a177c1e9077 | 8826cbf76bbac56dc9c5391c6cf8b663a82a4bca14409d237eec2a177c1e9077 | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
| 3ss3 é um t3st3 b3m gr@nd3 c0m v@ri0s símb0l0s! Incluínd0 núm3r0s (1234567890), c@r@ct3r3s 3sp3ci@is (!@#$%^&*), e l3tr@s m@iúscul@s e minúscul@s. 3st@ fr@se d3v3 s3r suficient3 p@r@ um b0m t3st3 d3 c0mp@r@çã0! | a6420b4dcfa2816bf1e513b8ad066b00ee97e92d5f778faa9070a9bf93c27aaa | a6420b4dcfa2816bf1e513b8ad066b00ee97e92d5f778faa9070a9bf93c27aaa | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
| Мензажем де тесте | 9967cdd87f3ce5a73fe3d5509a5fa3b4ae7300282f1851a17157e459e5d7cdfd | 9967cdd87f3ce5a73fe3d5509a5fa3b4ae7300282f1851a17157e459e5d7cdfd | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
| Μήνυμα δοκιμής | dd5592ac7d572bbd5b63bfd0126a99ad438e194d7d2d5ffc4e0f8e20cd013152 | dd5592ac7d572bbd5b63bfd0126a99ad438e194d7d2d5ffc4e0f8e20cd013152 | AES-256 (PyCryptodome) | AES-256 Decrypted (PyCryptodome) | AES-256 (Cryptography) | AES-256 Decrypted (Cryptography) |
