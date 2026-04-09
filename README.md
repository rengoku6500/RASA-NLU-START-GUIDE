nak mulakan bot rasa kena guna python container untuk lebih kestabilan


-------------------------------------------

cipta python container baru(sekali je):
python -m venv <name>

contoh:
python -m venv ./bekas1


-------------------------------------


pastu masuk dalam container tu:
<name>\Scripts\activate

contoh:
bekas1\Scripts\activate


--------------------------------------

cara guna bot

mula mula edit la 3 fail ni

- nlu.yml(untuk berikan dan ajar soalan)[ada di folder data]
- domain.yml(untuk berikan dan ajar jawapan)[ada di fail utama]
- stories.yml(untuk gabungkan soalan dan jawapan)[ada di folder data]


CARA EDIT:

1. mula mula masukkan soalan di nlu.yml cipta intent baru
2. lepastu cipta jawapan di domain.yml, cipta action baru dan listkan intent baru di bahagian atas sekali
3. lepastu baru gabungkan intent dan action di stories.yml



lepastu jalankan arahan ini

rasa train


lepastu jalankah salah satu dari arahan ni untuk debug

rasa shell nlu  (chat dengan verbose)

rasa shell (chat tanpa verbose)


-------------------------------------------------------------------------------------











