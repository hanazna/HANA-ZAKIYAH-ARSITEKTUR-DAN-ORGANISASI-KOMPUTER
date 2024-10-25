1. Pengalamatan Langsung:
Instruksi: LOAD A, 2000
Pada mode pengalamatan langsung, alamat operand langsung ditentukan oleh nilai yang ada di instruksi.
Alamat yang diakses: 2000

2. Pengalamatan Tidak Langsung:
Instruksi: LOAD A, (R1)
Dalam pengalamatan tidak langsung, nilai di register R1 dianggap sebagai alamat dari operand.
Jika R1 = 1500, maka alamat yang diakses adalah nilai yang terdapat di lokasi memori 1500.
Alamat yang diakses: 1500 (nilai yang ada di alamat ini menunjuk ke alamat operand yang sebenarnya).

3. Pengalamatan Indeks:
Instruksi: LOAD A, 500(R2)
Pada pengalamatan indeks, alamat operand dihitung dengan menjumlahkan nilai offset (dalam hal ini 500) dan nilai yang ada di register R2.
Jika R2 = 100, maka:
Alamat yang diakses: 500 +100 = 600

4. Pengalamatan Relatif:
Instruksi: LOAD A, 40
Dalam pengalamatan relatif, alamat operand dihitung dari posisi saat ini dalam program (alamat instruksi saat ini) ditambah dengan offset relatif yang diberikan (40).
Jika alamat instruksi saat ini adalah 1200, maka:
Alamat yang diakses: 1200 + 40 = 1240

5. Pengalamatan Segmen:
Segment Base: 4000 dan Offset = 300:
Pada pengalamatan segmen, alamat memori dihitung dengan menjumlahkan base dari segmen dengan offset yang diberikan.
Alamat yang diakses: 4000 + 300 = 4300

6. Latihan Campuran:
Instruksi: LOAD A, 1000(R3)
Pada pengalamatan campuran ini, instruksi memuat offset (1000) dan register R3.
Jika R3: 250, maka:
Alamat yang diakses: 1000 + 250 = 1250