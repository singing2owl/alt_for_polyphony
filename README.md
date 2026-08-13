## Development of a Neural Tool for Automatic Lyrics Transcription of Polyphonic Singing
## / Разработка нейросетевого инструмента для транскрипции текста многоголосного пения
### Tatiana Avdeeva / Татьяна Авдеева
### HSE University Computational Linguistics bachelor thesis
### / ВКР по компьютерной лингвистике (ФиКЛ, НИУ ВШЭ)

## 1. Отделение вокала от инструментала
Использовалась модель `model_bs_roformer_ep_317_sdr_12.9755.ckpt`.

## 2. Разделение голосов
Для отделения голосов друг от друга использовались модели `sepformer-libri2mix` и `sepformer-libri3mix` для 2-х и 3-х голосов соответственно.

## 3. Распознавание речи
Для транскрипции текста использовалась модель `Qwen3ASR-1.7B`.
