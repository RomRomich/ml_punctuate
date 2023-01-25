# Приложение восстанавливает пунктуацию и регистр для русского языка.

Задание по дисциплине программная инженерия магистратуры "Инжернения машинного обучения".

## Скрин экрана при работе приложения:

![image](https://user-images.githubusercontent.com/25247673/202898685-09ee299f-98cd-4774-9ebe-0d66e9730fc3.png)


## Описание используемой модели SbertPuncCase.

Модель расположена в комьюнити Hugging Face по адресу:
https://huggingface.co/kontur-ai/sbert_punc_case_ru

SbertPuncCase - модель восстановления пунктуации и регистра для русского языка. Модель способна расставлять точки, запятые и знаки вопроса; определять регистр - слово в нижнем регистре, слово с первой буквой в верхнем регистре, слово в верхнем регистре. Модель разработана для восстановления текста после распознавания речи, поэтому работает со строками в нижнем регистре. В основу модели легла sbert_large_nlu_ru. В качестве обучающих данных использованы текстовые расшифровки интервью.

## Примеры текста для преобразования

где продаются книги если идёт дождь

однако на улице прекрасная погода

где вы завтракали

на свете нет ничего что не могло бы случиться


## Запуск приложения:

streamlit run https://github.com/orgail/ml_punctuate/blob/main/streamlit_punctuate.py

Участники команды: 

Денис Самаркин
Роман Николаенко
Дмитрий Иванов
