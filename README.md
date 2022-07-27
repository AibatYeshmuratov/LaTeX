# LaTeX

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Что+я+изучил+на+курсе:)](https://git.io/typing-svg)
### Формулы
В LaTeX-е множество различных математических формул, которые помогут изложить материал правильно и грамотно. Здесь легко вставлять уравнения и математические формулы в документы, что придает им аккуратный и профессиональный вид. 
### Списки
Существует три типа списков. Первый - список enumerate, который создает нумерованный список. Второй - itemize, который используется для маркированных списков. Третий - список смешанный, который включает в себя, как маркированный, так и нумерованный списки.
### Таблицы
Таблицы в Latex создаются с помощью комбинации табличной среды и среды таблиц. Можно создать таблицы различного уровня с разными размерами ячеек + можно добавлять различные цвета в таблицы, прямо как в CSS.
### Картинки
Изображения в LaTeX-е являются неотъемлемой частью многих профессиональных документов. Это могут быть фотографии, графики, диаграммы или рисунки, которые добавляют информативности и ценности содержанию. В Latex можно увеличивать, уменьшать, поворачивать и устанавливать ссылку на изображение в документе.
### Литература
Можно добавлять цитирование из различных источников, а все используемые источники будут отображаться в разделе с Литературой, причем LaTeX следит за порядком добавления цитирования, так что не придется вручную добавлять нумерацию источников.

# Оглавление
[1. Установка](#установка)

[2. Структура](#структура) 

[3. Пакеты](#пакеты) 

[4. Формулы](#формулы) 

[5. Изображения](#изображения)  

[6. Оглавление](#оглавление)  

[7. Библиография](#библиография)   

[8. Сноски](#сноски) 

[9. Таблицы](#таблицы) 

[10. Гиперссылки](#гиперссылки) 

[11. Цвета](#цвета)

[12. Презентация](#презентация)


# Туториал по LaTeX

LaTeX — программа для верстки документов, обычно используется как язык разметки документов. LaTeX был создан для того, чтобы облегчить подготовку книг и статей общего назначения в рамках TeX. Поскольку LaTeX является расширением системы набора TeX, он обладает способностью TeX набирать технические документы, содержащие сложные математические уравнения. Язык разметки обрел популярность за счет очень качественного результата, стабильности и возможности менять документы под свой стиль.

LaTeX доступен практически для всех операционных систем, таких как Windows, Linux, Mac OS и многих других. Формат его файлов - обычный текст, который можно читать и редактировать на всех операционных системах. LaTeX будет выдавать одинаковые результаты на всех системах. 

Другими замечательными достоинствами LaTeX являются возможности добавления ссылок, автоматическая нумерация и создание заголовков, картинок, таблиц, ссылок, глоссариев и библиографий. Он является многоязычным и имеет специфические для каждого языка функции. За счет различных классов документов, LaTeX может быть удобен не только для научных работ. Здесь есть шаблоны для писем, презентаций, отчетов,  книг и статей. Сейчас доступно множество готовых шаблонов, стилей и инструментов, полезных для всех возможных целей.

Сам LaTeX не имеет графического интерфейса - это одна из причин, почему он так портативен. Вы можете выбрать любой текстовый редактор. Существует множество редакторов, специализированных для LaTeX, для каждой операционной системы. Некоторые редакторы доступны для нескольких систем. Например, TeXworks работает под Windows, Linux и Mac OS.

По умолчанию LaTeX выводит документы в формате PDF. Формат PDF широко используется во всем мире и доступен для просмотра на любых операционных системах без различий в форматировании. Наряду с PDF, вы можете выводить документы в PostScript, RTF, HTML, PNG, TIFF и другие форматы.



## Установка
Чтобы писать работы необходим IDE, удобнее всего использовать онлайн редакторы по типу overleaf. Однако существует и оффлайн редакторы, которые можно скачать на следующие операционные системы:
- Windiws
- Mac OS
- Linux

Для оффлайн версии можно скачать программу Texmaker. Программа включает мощный редактор файлов LATEX, подсветку синтаксиса, очень практичную и приятную систему автозаполнения формул, а также все команды для работы с MiKTeX. Для утановки программы зайдите на официальный сайт Texmaker: http://www.xm1math.net/texmaker/download.html. Далее, просто скачайте установочный файл, запустите его, следуйте инструкциям и оставьте параметры по умолчанию.

## Структура
Основная часть документа — это место между \begin{document} и \end{document}. Здесь можно добавить весь контент документа, включая название документа, титульный лист, автора/адрес/дату, оглавление, таблицы, рисунки, формулы, библиографию и т. д.

Перед созданием документа необходимо указать его класс. Класс документа определяет стандартный макет, в соответствии с которым LaTeX создаст ваш документ. Команда \documentclass, которая должна быть объявлена в начале, сообщает LaTeX, какой файл «.cls» использовать для текущего документа. Вот список классов документов в LaTeX:
- Article - обычно используется для создания статей научных журналов, документации, научных статей и т.д.;
- Letter - используется в создании писем;
- Books - для создания книг;
- Slides - для слайдов;
- Beamer - для создания презентаций
- Reports - обычно подходит для документов, содержащих несколько глав, подзаголовков, тезисов и т. д.
- 
Основные классы очень стабильны, но они также довольно консервативны как по дизайну, так и по набору доступных команд. Со временем был написан ряд более мощных классов, которые позволяют изменять дизайн без необходимости делать все вручную.



Чтобы добавить в документ заголовок, автора и дату, добавьте следующие строки в преамбулу, а не в основную часть документа:
- Для заголовка: \title{Глава первая}
- Для автора: \author{Автор}
- Дату: \date{Дата}
Чтобы в документе появился заголовок, имя автора и дата, используйте команду \maketitle, которая должна быть включена в тело документа.

Иногда в документе требуется указывать аннотации для этого в LaTeX-е есть предопределенные команды, которые сообщают ему, какая часть контента составляет аннотацию. Команда для включения аннотации существует только для класса документа, такого как Article и Report. Сама команда выглядит так \begin{abstract} Аннотации \end{abstract}.

Чтобы правильно структурировать свои работы в LaTeX-е существуют команды для создание заголовков и подзаголовков с автоматической нумерацией.
```LaTeX
    \section{}
    \subsection{}
    \subsubsection{}

    \paragraph{}
    \subparagraph{}
```
Для добавления различных разделов в ваш документ, вы можете использовать команды разделов, предоставляемые LaTeX. У каждого класса документа будут свои разделы, например, статья состоит из sections и paragraphs, а книга состоит из chapters.

LaTeX поддерживает нумерации страниц в документе. Нумерация страниц может быть переключена между римской и арабской цифрами. Для нумерации страниц используется команда \pagenumbering{...}, которая объявляется после команды \maketitle.

## Пакеты
Пакет обычно существует в виде файла или наборов файлов, содержащих определенные команды и программы, которые либо добавляют новые функции набора текста, либо изменяют уже существующие. Чтобы импортировать пакет в LaTeX, нужно просто добавить строку \usepackage{ИМЯ ПАКЕТА} в документе. Пакеты обычно используются для упрощения и разнообразия используемых функций, например существует пакет equation для математического режима.

Самые популярные пакеты LaTeX включают:
- esint: Добавляет больше вариаций интегралов;
- fancyhdr: Позволяет пользователям изменять верхний и нижний колонтитулы каждой страницы документа;
- geometry: Позволяет легче управлять полями и размером страницы в документе;
- glossaries: Позволяет создавать глоссарии и список аббревиатур в документе;
- hyperref: предоставляет LaTeX возможность управлять ссылками в документе;
- listings: Позволяет пользователям вставлять в документ программный код;
- longtable: Позволяет пользователям создавать таблицы, которые расширяются до следующей страницы;
- mathtools: Этот пакет дополняет ansmath и предлагает дополнительную функциональность;
- natbib: Предлагает новые стили и опции цитирования;
- rotating: Позволяет пользователям вращать объекты в документе;
- amsmath: Представляет продвинутые математические расширения для LaTex;
- array: Расширяет набор функций и возможностей настройки для таблиц в документе;
- biblax: Предлагает расширенную функциональность библиографии;
- booktabs: Предлагает дополнительные команды и опции оптимизации для таблиц;
- caption: Добавляет дополнительные возможности настройки внешнего вида и размещения подписей в таблицах, графических элементах и т.д.;
- cancel: Добавляет команды для зачеркивания математических выражений;
- changepage: Позволяет пользователям легко изменять поля страницы;
- cleveref: добавляет в LaTeX дополнительные возможности перекрестных ссылок;
- theorem: Позволяет изменять стиль новых теорем;
- ulem: позволяет подчеркивать текст с помощью прямой или волнистой линии;
- bibtex: добавляет библиографию;



## Формулы
С помощью множества предопределенных команд и сред можно набирать различные математичекие выражения с красивым и высококачественным выводом. По умолчанию LaTeX предоставляет все необходимые команды и среды для набора математического контента. Однако, пакет amsmath предоставляет больше возможностей, таких как различные виды выравнивания, нумерация уравнений и т. д. В качестве альтернативы вы можете использовать еще один пакет — mathtools.

Чтобы использовать формулы в документе, достаточно написать код формлуы со слэшем и обернуть все в знаки доллара. Более того формулы можно писать в отдельной строке, для этого нужно проделать тоже самой, только обернуть все в двойной знак доллара. Или использовать \begin{math}... \end{math}. Выражения могут быть как нумерованными так и без нумерации. Уравнения, пронумерованные одной строкой, могут быть созданы с помощью \begin{equation}...\end{equation}. Уравнения с несколькими строками могут быть созданы с помощью среды `eqnarray`. Однострочные ненумерованные уравнения могут быть созданы с любым из следующих кодов:
- \begin{displaymath} ... \begin{displaymath};
- \[ ... \];
- $$ ... $$

Более того, в LaTeX-е можно использзовать различные формы математических выражений, включая матрицы, дроби и т. д. Чтобы вставить математические дроби в документ, вы можете использовать следующий синтаксис \frac{числитель}{знаменатель}. Вы можете вставить матричное выражение в свой документ, используя среду `amsmath. Существует команда matrix, которую можно использовать для этой цели.
```LaTeX
\begin{matrix}

a & b\\

c & d

\end{matrix}
```

## Изображения
Изображения следует загружать отдельными файлами в популярных форматах, таких как .png, .jpg, .pdf или .jpeg. Вы можете скопировать изображения в архив проекта или по другому пути, и эти изображения можно загрузить с помощью \includegraphics. Для этой команды требуется пакет graphicx в преамбуле, который может быть загружен через команду \usepackage{graphicx}. Команда \includegraphics предоставляет множество параметров для форматирования изображения, например, настройку ширины, высоты, масштаба, углав поворота, обрезки и т. д.
```LaTeX
\documentclass{article}

\usepackage{graphicx}

\begin{document}

\begin{figure}
  \includegraphics[width=\linewidth]{green.jpg}
  \caption{Green color}
  \label{fig:green}
\end{figure}


\end{document}
```
У вас может быть несколько изображений в figure среде и одна подпись для каждого, например:
```LaTeX
\begin{figure}
\centerline{\includegraphics{image.jpg}}
\centerline{\includegraphics{another_image.jpg}}
\centerline{\includegraphics{also_image.jpg}}
\caption{Подпись}
\label{DM}
\end{figure}
```
Изображения относятся к плавающим объектам, это те объекты, которые плавают на страницах, не нарушая содержимое. Размещением этих плавающих элементов также можно управлять, указав расположение в квадратных скобках после {figure}. Существует следующие аргументы размещения объектов:
- h - здесь же, в том самом месте текста, где он появился;
- t - наверху страницы;
- b - внизу страницы;
- p - на специальной странице, содержащей только плавающие объекты;
- ! - игнорировать большинство параметров , которые могут предотвратить размещение этого объекта.

Для подписи картинок используют команду \caption{}, которая наберет подпись в нужном стиле и автоматически выдаст метку и номер. 

## Оглавление
Если вы пишете длинные отчеты, руководства, книги, диссертации и так далее, стандартной практикой является добавление оглавления. LaTeX имеет все возможности для выполнения этих классических требований. Оглавление обычно располагается в начале документа и перечисляет все главы и разделы в ней вместе с номером страницы. Если в документе есть заголовки и подзаголовки, то можно добавить оглавление, котоое создается автоматически с помощью одной команды \tableofcontents.
```LaTeX
\documentclass{article}

\begin{document}

\tableofcontents
\newpage

\section{Section}
Lorem ipsum .....

\subsection{Subsection}
Lorem ipsum

\end{document}
```
## Библиография
Для любой академической/исследовательской работы включение ссылок в документ является важной задачей. К счастью в LaTeX-е есть множество функций, которые значительно упрощают работу со ссылками. LaTeX имеет встроенную поддержку для цитирования ссылок. Однако гораздо более мощное и гибкое решение достигается благодаря вспомогательному инструменту BibTeX (который входит в стандартную комплектацию Latex).

С помощью расширения bibtex можно добавлять используемые источники, для этого нужно отедльно создать файл с расширеним .bib, который будет содержать источники в формате LaTeX. Далее в самом документе нужно добавить команды \bibliography, сообщающие LaTeX о расположении нашего файла .bib, и \bibliographystyle, которая выбирает один из различных библиографических стилей. Синтаксис фала .bib выглядит следующим образом:
```LaTeX
@BOOK{Name: 1
AUTHOR="Автор",
TITLE="Название"
PUBLISHER="Издательство",
YEAR="Дата"
}
```
Каждая запись начинается с объявления типа ссылки в виде @TYPE. BibTeX знает практически все типы, которые только можно придумать, такие распространенные, как книга, статья и т.д. После типа должна стоять левая фигурная скобка '{', обозначающая начало атрибутов ссылки. Первый атрибут следует сразу после скобки - это ключ цитирования. Этот ключ должен быть уникальным для всех записей в вашей библиографии. Именно этот идентификатор вы будете использовать в своем документе для перекрестных ссылок на эту запись. Вы сами решаете, как обозначить каждую ссылку, но существует общепринятый стандарт, согласно которому используется фамилия автора, за которой следует год публикации. Далее следуют соответствующие поля и данные для данной конкретной ссылки. Названия полей слева - это ключевые слова BibTeX. За ними следует знак равенства =, куда затем помещается значение для этого поля.


## Сноски
Создать сноски можно с помощью команды \footnote и пометить их с помощью \label, номер сноски генерируется автоматически. Формат номера сноски можно изменить с помощью следующих команд:

- \renewcommand{\thefootnote}{\arabic{footnote}}}} - Арабские цифры;
- \renewcommand{\thefootnote}{\Roman{footnote}}}} - Римские цифры;
- \renewcommand{\thefootnote}{\alph{footnote}}}}- Буквенные;
- \renewcommand{\thefootnote}{\Alph{footnote}}}} - Буквенные верхний регистр;
- \renewcommand{\thefootnote}{\fnsymbol{footnote}}}}- Последовательность из символов;

## Таблицы
В LaTeX-е существует отдельная табличная среда для создания таблиц. Такая среда предназначенна для форматирования данных в красиво оформленные таблицы. После объявления среды требуются аргументы для описания выравнивания каждого столбца. Количество столбцов указывать не нужно, так как оно определяется по количеству аргументов. Здесь также можно добавить вертикальные линии между столбцами. Для описания столбцов таблицы можно использовать следующие символы:
- l выровненная по левому краю колонка;
- c центрированная колонка;
- r выровненная по правому краю колонка;
- | вертикальная линия;
- || двойная вертикальная линия;

Синтаксис самой базовой таблицы вглядит следующим образом:
```LaTeX
\begin{tabular}{ l c r }
  1 & 2 & 3 \\
  4 & 5 & 6 \\
  7 & 8 & 9 \\
\end{tabular}
```
Чтобы добавить линии между столбцами, используейте символы линии между l, c, r, команда \hline добавит, в свою очередь, горизонтальные линии.

## Гиперссылки
Добавьте пакет гиперссылки в преамбулу вашего документа с помощью команды \usepackage{hyperref}. Пакет hyperref позволит вам добавлять ссылки с описанием по вашему выбору, а также устанавливать URL-адреса в ваш документ LaTeX. После добавления пакета hyperref вы можете добавлять или устанавливать гиперссылки в любом месте документа с помощью команды \href . Ниже приведен пример, чтобы понять использование:
```LaTeX
\documentclass{article}
\usepackage{hyperref}
\begin{document}
Текст ...
Гиперссылка:  \href{http://www.wikipedia.com}{Click Here}
\end{document}
```
Если вы хотите изменить настройки цвета гиперссылки по умолчанию, вы должны использовать команду \hypersetup в преамбуле вашего документа.

## Цвета
При подготовке документа в LaTeX вы можете захотеть использовать цвета для различных целей. Это может быть окрашивание текста или выделение текста путем изменения цвета фона. В LaTeX-е доступно множество вариаций использования цвета, здесь будут описаны лишь некторые.

Чтобы раскрасить текст в документе, сначала нужно добавить пакет color или xcolor в преамбулу вашего файла LaTeX. Однако пакет xcolor имеет более мощные возможности, чем пакет color. Используйте следующую команду для изменения цвета текта \textcolor{colorname}{Текст для окрашивания}. С подключеним xcolor вам будет доступен набор цветов по умолчанию.  Стандартные увета включают в себя: красный, зеленый, синий, голубой, пурпурный, желтый, черный, серый, белый, темно-серый, светло-серый, коричневый, лайм, оливковый, оранжевый, розовый, пурпурный, тиловый, фиолетовый. Можно смешивать несколько цветов для получения нового цвета, как показано ниже на примере:
```LaTeX
Обычный цвет {\color{green!55!blue}кастомный цвет}
```
Для выделения текста, помимо загрузки пакета color или xcolor, нам также необходимо загрузить пакет soul. Теперь текст можно выделить, просто используя команду \hl{text}.
```LaTeX	
\usepackage{soul}
Обычный текст \hl{выделенный текст}
```
По умолчанию текст выделяется путем изменения цвета фона на желтый. Можно изменить цвет выделения на желаемый, для этого пакет soul предоставляет команду \sethlcolor{colorname} для изменения цвета подсветки. Например, мы можем изменить цвет на зеленый:
```LaTeX	
\usepackage{xcolor}
\usepackage{soul}
\sethlcolor{green}
 ```	
Если вы хотите добавить свой собственный цвет, которого не нашли в стандартных, то это можно сделать с помощью пакет xcolor. Новые цвета могут быть определены с помощью команды \definecolor.

Для подчеркивания текста в LaTeX по умолчанию используется команда \underline, который хорошо работает в большинстве случаев, но не обладает большой гибкостью. Чтобы получить текст с цветным подчеркиванием, нам придется снова воспользоваться внешним пакетом soul. Этот пакет обеспечивает дефисное начертание букв, подчеркивание, надчеркивание и выделение с набором опций для их настройки. При использовании этого пакета подчеркнутый текст создается с помощью команды \ul. По умолчанию подчеркивания черные. Это можно изменить с помощью команды \setulcolor в любой точке текста. 
```LaTeX	
\setul{0.3ex}{0.2ex}
\begin{document}
\setulcolor{Green}
\ul{Подчеркнутый текст}\\
```	


## Презентация
В LaTeX-е существует класс документа под названием Beamer. Это класс документов LaTeX, который используется для создания презентаций.  Beamer предоставляет библиотеку с различными темами. Таким образом, мы можем настроить макет презентации, изменив всего несколько строк в коде LaTeX. Также можно создавать и импортировать новые темы, делая процесс настройки презентации еще более мощным. Различные виды шаблонов и набор интересных функций для создания красивых презентаций можно найти в галерее Overleaf. Вот пример синтаксиса класса beamer
```LaTeX
\documentclass{beamer}

\title{Заголовок}
\subtitle{Подзаголовок}

%\usetheme{Madrid}
\begin{document}
	\frame {
		\titlepage
	}
	\frame {
		\frametitle{Страница 1}
		Lorem ipsum ...
	}
	\frame{
		\frametitle{Страница 2}
		\begin{itemize}
			\item 1
			\item 2
			\item 3
		\end{itemize}
	}
	\frame{
	    \frametitle{Формула}
	    $E = mc^2$.
	}
\end{document}
```
После указания класса beamer обычно определяют основную информацию о презентации. Наиболее распространенная информация на этом этапе состоит из названия презентации, имени авторов, названия института или компании и даты. Мы можем добавить эти определения, используя приведенные ниже строки:
```LaTeX
\title{Beamer Presentation Title}
\author{Presentation Authors' Name}
\institute{Institute or Company Name}
\date{Presentation Date}
```
Далее в теле документа создаются фреймы, которые можно редактировать и добавлять собственный контент. По умолчанию, только ввод текста в область видимости фрейма приводит к тому, что после компиляции текст выравнивается по центру фрейма по вертикали. Рассмотрим следующее возможности редактирования содержания фрейма.

Можно изменить выравнивание текста во фрейме. Это можно сделать, вставив команду расположения в фигурные скобки в \begin{} и  (\end{}. Доступные варианты выравнивания: справа (flushright), слева (flushleft) и по центру (center).

Мы можем добавить изображения в рамку презентации. Для этого мы используем стандартную область фигур LaTeX. Например:
```LaTeX
\begin{figure}
    \includegraphics{image.png}
    \caption{Image}
\end{figure}
```
Помимо темы по умолчанию, пакет Beamer предоставляет темы: AnnArbor; Antibes; Bergen, Berkeley, Berlin, Boadilla, CambridgeUS, Copenhagen, Darmstadt, Dresden, Frankfurt, Goettingen, Hannover, Ilmenau, JuanLesPins, Luebeck, Madrid, Malmoe, Marburg, Montpellier, Pittsburgh, Rochester, Singapore, Szeged, and Warsaw.

Здесь перечислены лишь некоторые из свойств и функций LaTeX-а, на самом деле существует множество других не менее инересных особенностей данной разметки. Более подробную информафию можно найти в официальное документации и на сайте overleaf.com.

