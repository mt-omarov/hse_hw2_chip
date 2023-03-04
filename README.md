# hse_hw2_chip

## Ссылка на мою тетрадь google colab находится [здесь](https://colab.research.google.com/drive/1cycwmIvOTM25VnJ9aH3g1dpRJHQPjM-t?usp=sharing).

## Результаты FASTQC
Качество чтений файлов всех трёх последовательностей оказалось приемлемым, их можно наблюдать ниже.
- контрольный файл ENCFF001FFI \
  <img width="526" alt="image" src="https://user-images.githubusercontent.com/95280619/222914671-3148ca6c-d701-4382-b860-8da8f0c91e4e.png">
  <img width="526" alt="image" src="https://user-images.githubusercontent.com/95280619/222914659-a82c1c0a-9fdb-4444-91c7-a46c250f8483.png">

* 1ая реплика ENCFF001FEM \
  <img width="526" alt="image" src="https://user-images.githubusercontent.com/95280619/222914554-a3d7e859-258e-4663-8fc6-9f8dbb30b153.png" width="385px">
  <img width="526" alt="image" src="https://user-images.githubusercontent.com/95280619/222914623-f6194754-3257-44e9-b7d0-2686787e373b.png" width="385px">
  
* 2ая реплика ENCFF001FEP \
  <img width="526" alt="image" src="https://user-images.githubusercontent.com/95280619/222914697-83b4e978-2179-4b5d-9063-ca3520d4f5b0.png">
  <img width="526" alt="image" src="https://user-images.githubusercontent.com/95280619/222914703-ba12c16c-8103-43df-9099-ae2250718775.png">

## Таблица со статистикой выравнивания по хромосоме 13
<p align="center">
  <img width="771" align="center" alt="image" src="https://user-images.githubusercontent.com/95280619/222914997-9e31c3cb-cadd-4a6e-bd93-e2990bf9f143.png">
</p>

**Ответ на вопрос о проценте выравниваний:** \
Процент выравниваний в последовательностях оказался низким именно потому, что выравнивание производилось только по одной хромосоме, другие игнорировались.

## Диаграммы Венна
<p align="center">
  <img width="771" alt="image" src="https://user-images.githubusercontent.com/95280619/222915723-9e16814d-75e5-44f1-995b-0e28ac5a6952.png">
  <img width="771" alt="image" src="https://user-images.githubusercontent.com/95280619/222915785-dcef315b-c035-4631-ad79-3f4fe916fcc1.png">
  <img width="771" alt="image" src="https://user-images.githubusercontent.com/95280619/222915762-add30681-e05d-442d-b57b-3156e4c5f295.png">
</p>

**Пояснение:** \
Пересечений между полученными нами результатами и ождимаемыми результатами с сайта ENCODE довольно мало, поскольку мы выравнивали последовательности только для хромосомы 13, тогда как на сайте ENCODE последовательности были выравнены по всем хромосомам.
