CARA EDIT BOT


ada di fail 'data'
nlu.yml (untuk berikan soalan)
stories.yml ( untuk gabungkan soalan dan jawapan)


ada di fail utama
domain.yml (untuk berikan jawapan)




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

mula mula edit la 4 fail ni

nlu.yml
stories.yml
domain.yml


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











