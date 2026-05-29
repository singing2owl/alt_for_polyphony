## Development of a Neural Tool for Automatic Lyrics Transcription of Polyphonic Singing
### Tatiana Avdeeva
### HSE Computational Linguistics bachelor thesis

## 1. Отделение вокала от инструментала
Был [протестирован](https://colab.research.google.com/drive/1NZbreNoOy6ZASLQB_jIaXLuDLYgwiYhr?usp=sharing) [Python Audio Separator](https://github.com/nomadkaraoke/python-audio-separator), лучшая модель на данный момент - vocals_mel_band_roformer. Полностью оправдывает ожидания.

## 2. Разделение голосов
Использовался код из [репозитория Константина Пинкла](https://huggingface.co/Tino3141/sepacap/tree/main).

Несмотря на заявленное в [работе](https://huggingface.co/papers/2509.26580) качество, тестирование не дало приемлемых результатов, что ожидаемо с учётом явного переобучения модели.

## 3. Singing-to-speech

Был протестирован код из [репозитория Jiawen Huang](https://github.com/jhuang448/singing-to-speech).

Результат также оставил желать лучшего: хоть аудио действительно стало походить на устную речь больше, чем на пение, разобрать текст из него было бы сложно.
