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
|--------|--------------|------------|--------------------|--------------------|
| a | ca978112ca1bbdcafac231b39a23dc4da786eff8147c4e72b9807785afee48bb | ca978112ca1bbdcafac231b39a23dc4da786eff8147c4e72b9807785afee48bb | 7YeB0mf5uUxrIk+/U4U1kljwyaIvccAkXNB2MSmtILQ= | HPZVZk57VzVjRwp1DWxuzOzvfEGdKAMx8FlV6cKeWG0= |
| El Psy Kongroo | d048c15f016e7a3bb99759f6ea0c8c65bac9e2e811a04b4d8a6a3d0f02ce021b | d048c15f016e7a3bb99759f6ea0c8c65bac9e2e811a04b4d8a6a3d0f02ce021b | MHfpe7w8qx/bIFnBA03ceo420CnDWqddye3beas7IEE= | yoqwvbY7OcVpI8mqTx2iw1MAmkEGUHWxXPqCcCAqypI= |
| 1.048596 | d8f998989e7c76ed742659f50502b295172f764dd72517f75451c7493478b8ec | d8f998989e7c76ed742659f50502b295172f764dd72517f75451c7493478b8ec | DeRKZLOuzL4QIFklzG1yoC0bdnf9MfZBeeUSxjke1Wc= | l+LJec8VH5EY+RtUhET/TPfDh8CR8UkHWbkx49F6ark= |
| お前はもう死んでいる. | cb5ee74895ff1ebf77c53669037cb5528a6375dc9dc72c5628198066a59f83e1 | cb5ee74895ff1ebf77c53669037cb5528a6375dc9dc72c5628198066a59f83e1 | HM8+CODO2SCCsfkLBNaeADSf4sKWeLEIFo/I2qRV3vyypLLGFBvdF0K8L80oIiwo | iMAfo3ByU4b699WlHnl+qWca3YV1axaifhcgthn6vdfC42tyydHGDchPcYyK7z1Z |
| Para obter algo, é preciso oferecer algo de igual valor. | 12b9298f5fdbefb4f6963f48fec0e40b5e0ee538ce3af479e5e39adec089d879 | 12b9298f5fdbefb4f6963f48fec0e40b5e0ee538ce3af479e5e39adec089d879 | bCLeb7+PW0aW1rQkPG8QLDX8LTZnoKcK2rRUb/lxRv99VBH0DB3mw6ItnhvXBEpNwxFN7q7unVGrmjgrS4mVatNaxPn13A7BNFZo9DKEYOg= | jqo4pN0nDRRVh4rWcPNltlBD2ptSoWMCH3QPm2VR7a1kuv4xxdh6+3VkI1q/Nx1jA2s6sz0LtDVqqnpmLY8Q1W7nvxjznGg7/NDrfcf4uNw= |
| Exemplo de teste | 378fe99acbb988f49ff6b2c67285e5a67a0baac9c135ccf4f6748c4b20b9337a | 378fe99acbb988f49ff6b2c67285e5a67a0baac9c135ccf4f6748c4b20b9337a | IjrpUeaV6ztxUkZr8837W4YcZht9qgG11HxN7ckpd8wTX63+XiAc9UhmPq2KKi5L | 5niDhAKLwS7VYro3DZm0oBGQimgKQE6v83hH4h9NyCD8nyUHTNDp/UuyMIQYNjdG |
| 3ss3 t3st3 contém vári0s símb0l0s dif3r3nt3s! | 8826cbf76bbac56dc9c5391c6cf8b663a82a4bca14409d237eec2a177c1e9077 | 8826cbf76bbac56dc9c5391c6cf8b663a82a4bca14409d237eec2a177c1e9077 | rJU/dJ1rQPNNIS/SJOeUY6Ni7/QB5mvYgUxaixXGOJ1cufUbVkmcSv5VuWU80G/uDKP+De5NEnw+RMfdt7qfkQNX+HerGG1XNQY2jWK1STc= | e0t52cDPixWCYgi8qAk2zxgf/adoTOVkGf235xhmRkavwIhOUdBmJltYkRev8NlPhHTG/UBPv0a64Kbk0Q0pN3r4jdIE7v/TFVHCaXMykCU= |
| 3ss3 é um t3st3 b3m gr@nd3 c0m v@ri0s símb0l0s! Incluínd0 núm3r0s (1234567890), c@r@ct3r3s 3sp3ci@is (!@#$%^&*), e l3tr@s m@iúscul@s e minúscul@s. 3st@ fr@se d3v3 s3r suficient3 p@r@ um b0m t3st3 d3 c0mp@r@çã0! | a6420b4dcfa2816bf1e513b8ad066b00ee97e92d5f778faa9070a9bf93c27aaa | a6420b4dcfa2816bf1e513b8ad066b00ee97e92d5f778faa9070a9bf93c27aaa | eZc3tDMLS78zH1GCwTMg6IYWr5OMY6BO3L303FhIP0N8YWHPBDIp7/f9MT35Bvzj0XVmrD7yE9DdtzoB2zLtaU3HJuOR+hp5W5s8FD3vW3dbOEeROt43cL82JMhPAXgPU+4T1fl+MlogWsWb3CdFKBJZTUwqtSEDAAnpaBVMz7AkslKpquzkepXqBhFuNml1FPRwfN6L4Q+PPsYDIh+7VdVMIKFRfAHJThKkYjpDAfCfqKUT7gF/1rUnoW/Fp1QMjM62mmFpBZhr3UfUpRgmBdTDEbz/zxudgFLOd+7zzR407K1n4e/p2HBFG90T4S+w | dHWfZ+2tW9OsoMdoWfmEP9UifEQhYYYGRNdyxO20Gr502dh1Z0bZKKDmyYLktalNB4gLbfcRK5Wb/s8qD35pu1ZoBbzBVJWpFKVrg0EuJgydM6F2V13Px/s9uaZwg/B8FM435cmwm/y+MVjNpKyBFeLLy9yJQoL/qaSTZsQZHPUoWP4QIFZHsU0tvGR/SuK3PX2p2exNygrupFo7HzQmbXTaZe1fIIh2nkcuBVFgSxqrbsN9HjZzU6xjxVj+qyKdsUJMyYUbwnvVb/U/gqMfpecFhNt4lOQ9Nbmb4xaaziO31BKLSGF/JL7q3AtaPEKO |
| Мензажем де тесте | 9967cdd87f3ce5a73fe3d5509a5fa3b4ae7300282f1851a17157e459e5d7cdfd | 9967cdd87f3ce5a73fe3d5509a5fa3b4ae7300282f1851a17157e459e5d7cdfd | V8KUWeW8zAW22n2RjcOwjI2FDa2Edf5923Y/6Uwb1hOQnlPt07guUmUxTMM/EFLqsMFqnxfr3X0oYNOGMD9lfQ== | JmwFAvz3uBYJoGJ2CXUn5LtiKdM9NeQVTOMDKZIUASaaLzmkJnTArsTgoiqtSYBRAfZt4/3EWF0hJ/4dd9Fa+g== |
| Μήνυμα δοκιμής | dd5592ac7d572bbd5b63bfd0126a99ad438e194d7d2d5ffc4e0f8e20cd013152 | dd5592ac7d572bbd5b63bfd0126a99ad438e194d7d2d5ffc4e0f8e20cd013152 | 2s9q2EGGlqgP98ufKx7BFEIXChRv18Osae9NHK056Ol6Z4S3rOsAJB4eynZjWoOn | OczfVm28AmiiIPb7yYWZcICS47JX8eCTZCPyJxugaKvPee8Hj6Bayn+uHxrXZ4be |

### 1. **Análise Comparativa entre SHA-256 e AES-256**

#### 1.1 Introdução

&ensp; SHA-256 e AES-256 são algoritmos criptográficos amplamente utilizados, cada um com um objetivo diferente [(STALLINGS, 2018)](#5-referências). Enquanto SHA-256 é uma função de hash utilizada para garantir a integridade dos dados e verificação de autenticidade, AES-256 é um algoritmo de criptografia simétrica voltado para a proteção de informações sigilosas. Esta análise compara ambos com base em velocidade, segurança e aplicabilidade, utilizando resultados experimentais baseados em testes práticos.

#### 1.2 Comparativo

###### Propósito

 - SHA-256 é uma função de hash projetada para garantir a integridade dos dados, gerando um valor único e irreversível a partir de um input;

- AES-256 é um algoritmo de criptografia simétrica que protege a confidencialidade dos dados, permitindo que informações criptografadas sejam recuperadas com uma chave correta.

##### Irreversibilidade vs. Reversibilidade

- SHA-256 é um processo unidirecional, ou seja, não é possível obter os dados originais a partir do hash gerado [(FERGUSON; SCHNEIER; KOHNO, 2010)](#5-referências).

- AES-256 é reversível, pois os dados podem ser recuperados caso se tenha acesso à chave de descriptografia.

##### Velocidade

&ensp; Com base nos testes realizados utilizando as bibliotecas PyCryptodome e Cryptography, observou-se que SHA-256 apresentou um desempenho superior em termos de velocidade em relação ao AES-256.

&ensp; Isso ocorre porque SHA-256 processa os dados de maneira linear, gerando um hash fixo de 256 bits, enquanto AES-256 executa múltiplas rodadas de encriptação e requer um bloco de inicialização (IV), tornando-o mais pesado computacionalmente.

##### Segurança

&ensp; SHA-256 possui alta resistência a colisões e é amplamente utilizado para validação de integridade e assinaturas digitais [(KATZ; LINDELL, 2020)](#5-referências). No entanto, ele não protege a confidencialidade dos dados, pois não permite recuperá-los.

&ensp; AES-256 é considerado um dos algoritmos de criptografia mais seguros, sendo utilizado para transmissão de informações sensíveis, armazenamento seguro de dados e comunicações protegidas.

#### 2. Uso

- **SHA-256**:

&ensp; Principalmente usado para autenticação, blockchain, verificação de integridade de arquivos e proteção de senhas (hashing).

- **AES-256**:

&ensp; Utilizado em segurança de redes, armazenamento de dados sigilosos, proteção de informações bancárias e criptografia de comunicações.

#### 3. Aplicabilidade

- **SHA-256**:

  -  Blockchain;

  -  Certificação digital;

  -  Hashing de senhas;

  -  Controle de integridade de arquivos.
<br>

- **AES-256**:

  -  Proteção de comunicações seguras;

  -  Armazenamento de informações sensíveis;

  -  Segurança de transações bancárias;

  -  Critografia de arquivos e discos;
<br>

#### 4. Explicação do código
&ensp; Os dois códigos apresentados realizam testes de criptografia e hashing, utilizando os algoritmos AES-256 e SHA-256. O primeiro código implementa a criptografia AES-256, que é um método de criptografia simétrica utilizado para proteger dados sensíveis. Ele emprega a biblioteca PyCryptodome e a Cryptography para criptografar e descriptografar uma lista de frases, garantindo que os dados possam ser recuperados apenas com a chave correta. O segundo código implementa a função de hash SHA-256, que é um algoritmo de hash criptográfico usado para gerar resumos únicos e irreversíveis de dados. Ele utiliza as bibliotecas hashlib e PyCryptodome para transformar cada frase de teste em um hash de 256 bits, permitindo verificações de integridade e autenticação sem a possibilidade de reversão ao valor original. Enquanto o AES-256 foca na proteção de informações confidenciais garantindo confidencialidade, o SHA-256 é utilizado para garantir a integridade dos dados, tornando-se essencial para segurança digital e aplicações como *blockchain* e autenticação de dados.

#### 5. Conclusão

&ensp; Os resultados dos testes realizados confirmam que SHA-256 é mais eficiente em termos de velocidade, pois requer menos processamento. Por outro lado, AES-256 é essencial para a segurança de informações sigilosas devido à sua capacidade de proteção contra acessos não autorizados.

&ensp; A escolha entre SHA-256 e AES-256 depende do objetivo desejado. Para garantir integridade e autenticidade, SHA-256 é mais adequado. Para proteger a confidencialidade dos dados, AES-256 é a escolha ideal. Ambos possuem pontos fortes em suas respectivas funções e são essenciais para a segurança digital.

#### 6. Referências 

- FERGUSON, N.; SCHNEIER, B.; KOHNO, T. Cryptography Engineering: Design Principles and Practical Applications. Wiley Publishing, 2010.

- KATZ, J.; LINDELL, Y. Introduction to Modern Cryptography. 3. ed. CRC Press, 2020.

- SCHNEIER, B. Applied Cryptography: Protocols, Algorithms and Source Code in C. 2. ed. Wiley, 1996.

- STALLINGS, W. Cryptography and Network Security: Principles and Practice. 7. ed. Pearson, 2018.