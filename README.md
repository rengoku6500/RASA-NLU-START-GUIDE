# Nak Mulakan Bot Rasa

Nak mulakan bot rasa kena guna python container untuk lebih kestabilan

---

## Cipta Python Container Baru (sekali je)

```bash
python -m venv <name>

Contoh:

python -m venv ./bekas1
Masuk Dalam Container
<name>\Scripts\activate

Contoh:

bekas1\Scripts\activate
Cara Guna Bot

Mula mula edit la 4 fail ni:

nlu.yml (untuk berikan dan ajar soalan) [ada di folder data]
domain.yml (untuk berikan dan ajar jawapan) [ada di fail utama]
stories.yml (untuk gabungkan soalan dan jawapan) [ada di folder data]
Cara Edit
Mula mula masukkan soalan di nlu.yml, cipta intent baru
Lepastu cipta jawapan di domain.yml, cipta action baru dan listkan intent baru di bahagian atas sekali
Lepastu baru gabungkan intent dan action di stories.yml
Jalankan Arahan
rasa train

Lepastu jalankah salah satu dari arahan ni untuk debug:

rasa shell nlu  # chat dengan verbose
rasa shell      # chat tanpa verbose
