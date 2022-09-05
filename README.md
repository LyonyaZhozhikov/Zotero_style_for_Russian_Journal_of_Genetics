# Стиль Zotero для журнала "Генетика"

about journal (at 2022) - [![Badge](https://img.shields.io/static/v1?label=Russian_Journal_of_Genetics&message=Q4&color=blueviolet?style=for-the-badge&logo=scopus)](https://www.springer.com/journal/11177)

#### Что в этом репозитории?
Здесь находится стиль библиографии для Zotero (Juris-M), который соответствует требованиям журнала "Генетика". 
Подойдет для тех, кто пользуется Zotero и планирует там публиковаться.

#### Какие требования соблюдаются в этом стиле?
1. Номера ссылок в тексте в квадратных скобках (например [1], [2–5])
2. Фамилии и инициалы авторов курсивом
3. При наличии четырех авторов статьи указываются все, а более четырех – только первые три, и
далее “и др.” или “et al.”.
4. Все метаданные цитируемых статей сокращены до однобуквенного значения (Том -> Т., Vol. -> V., и тд)
5. DOI с новой строки
6. Стиль учитывает язык статьи, если он русский то адаптирует его под соответствующий формат (Volume -> Tом, Page -> Cтраница), 
при остальных языках стиль по умолчанию оставляет английские обозначения страниц и томов.

#### Пример результата работы стиля при оформлении библиографии:
<div id="header" align="left">
  <img src="https://github.com/LyonyaZhozhikov/Zotero_style_for_Russian_Journal_of_Genetics/blob/main/data/example_word.bmp" width="600"/>
</div>

#### Чего этот стиль НЕ делает?
1. Стиль не форматирует особым форматом статьи журнала "Генетика", как этого требует редакция. (обозначать такие статьи двойным цитированием, 
например после русскоязычного цитирования в библиографии в скобках указать англоязычное цитирование). При подобном случае необходимо указать это в скобках вручную.
2. Стиль пока работает только с научными статьями и не распознаёт книги, главы и диссертации.
3. Данный стиль требует установки Juris-M для распознавания разных языков (это приложение которое устанавливается поверх Zotero и в целом такое же внутри).

---

### Для тех, кто не знаком с тем как пользоваться Zotero, но хочет пользоваться данным стилем:
1. Необходимо скачать и установить Zotero (1) и его расширение (2) на тот бразуер, которым Вы пользуетесь. 
После этого зарегистрироваться на сайте Zotero и синхронизировать Ваш аккаунт с самим приложением. 
Если вы планируете писать текст с начала, то следует скачать также расширение в Word (3), или в другое приложение, где Вы пишите сами статьи.
2. Также нужно скачать, установить и синхронизировать отдельно приложение Juris-M (4), это идентичное Zotero (1) приложение которым можно далее пользоваться вместо Zotero.
3. Используя расширение браузера (2), набрать литературу в вашу библиографию (необходимо чтобы приложение Zotero (1) было в это время открыто). 
Либо любым другим способом.
4. (если возникают трудности на каком-то этапе лучше посмотреть видео на YouTube)
5. Скачать файл russian-GOST-2008-modified-for-Russian_Journal-of-Genetics.csl с этого репозитория, 
либо полностью скопировать его содержимое в пустой блокнот и сохранить как файл с расширением .csl
6. В приложении Juris-M (4) или Zotero (1) зайти в Правка -> Настройки -> Цитирование -> + -> найти и открыть ваш файл со стилем .csl
7. После того как стиль установлен, можно им пользоваться выбрав в списке Стили -> Диспетчер стилей, 
либо во вкладке Zotero в расширении Word (3) -> Document preferences.

#### Советы при написании статьи данным стилем:
1. Так как жур. "Генетика" требует цитирования по мере упоминания в статье, то следует установить расширение в Word (3) и приноровиться к нему.
2. После написания статьи подогнать поля, межстрочный интервал и тд. библиографии (тк автоматически выставить интервал в 1.5 в Zotero (1) пока невозможно).
3. Если у вас есть в библиографии статьи на русском и английском языке, установка Juris-M (4) обязательна, 
так как именно это приложение распознаёт два языка (Zotero (1) пока такого не может).
4. Если в библиографии присутствуют статьи только на одном языке и нет совсем желания устанавливать Juris-M (4) :) 
то можно во второй строчке кода в default-locale поменять язык на необходмиый; по умолчанию стоит default-locale="en-US" его можно поменять на "ru-RU".

---