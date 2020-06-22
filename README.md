# Time series course for Sberbank staff, summer 2020.
 
### Программа курса
* неделя 1 - основные понятия и статистики временных рядов
* неделя 2 - авторегрессионные методы и переход к supervised задаче
* неделя 3 - поиск аномалий и метрики качества
* неделя 4 - нейросетевой подход к предсказанию
* неделя 5 - классификация временных рядов

### Домашнее задание
* дается на каждую неделю
* 10 баллов за каждую
* мягкий дедлайн - начало каждой следующей недели
* присылать в telegram - @technogleb с указанием фамилии и номера недели

### Технические моменты
* python3.7
* виртуальное окружение  
`python3.7 -m venv .env`
`source .env/bin/activate`  
`virtualenv -p python3.7 .env` `source .env/bin/activate`
* держать актуальным окружение  
`pip install -r requirements.txt`
* чтобы были доступны импорты  
*nix: `export PYTHONPATH=$PYTHONPATH:~/ts_course_summer`  
win: `set PYTHONPATH=%PYTHONPATH%;C:\ts_course_summer`
