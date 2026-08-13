## Development of a Neural Tool for Automatic Lyrics Transcription of Polyphonic Singing
### HSE University Computational Linguistics bachelor thesis
### Tatiana Avdeeva

A brief project poster can be found [here](https://github.com/singing2owl/alt_for_polyphony/blob/main/Avdeeva_ALT_for_polyphony_slides.pdf) (ru).

Defence slides describing the project are available [here](https://github.com/singing2owl/alt_for_polyphony/blob/main/ALT_for_1_3_voices.ipynb).

### 1. Separating vocals from background music
We used the following model: `model_bs_roformer_ep_317_sdr_12.9755.ckpt`.

### 2. Singer separation
To separate singer voices from each other the following models were used: `sepformer-libri2mix` and `sepformer-libri3mix` for 2 and 3 voices correspondently.

### 3. Automatic Speech Recognition
`Qwen3ASR-1.7B` was used for the purpose of lyrics transcription.

## Разработка нейросетевого инструмента для транскрипции текста многоголосного пения
### ВКР по компьютерной лингвистике (ФиКЛ, НИУ ВШЭ)
### Татьяна Авдеева

Краткое изложение идеи и результатов работы представлено на [постере](https://github.com/singing2owl/alt_for_polyphony/blob/main/Avdeeva_ALT_for_polyphony_slides.pdf).

Презентация с защиты ВКР доступна по [ссылке](https://github.com/singing2owl/alt_for_polyphony/blob/main/ALT_for_1_3_voices.ipynb).

### 1. Отделение вокала от инструментала
Использовалась модель `model_bs_roformer_ep_317_sdr_12.9755.ckpt`.

### 2. Разделение голосов
Для отделения голосов друг от друга использовались модели `sepformer-libri2mix` и `sepformer-libri3mix` для 2-х и 3-х голосов соответственно.

### 3. Распознавание речи
Для транскрипции текста использовалась модель `Qwen3ASR-1.7B`.
