## Приложения к книге "Статистический анализ и визуализация данных с помощью R"

Этот репозиторий содержит файлы R-скриптов и наборы данных, необходимые для воспроизведения примеров из электронной книги _Мастицкий С.Э., Шитиков В.К. (2014) "Статистический анализ и визуализация данных с помощью R"_. Данное пособие обобщает серию методических статей по языку R, опубликованных в 2011-2014 гг. в блоге ["R: Анализ и визуализация данных"](http://r-analytics.blogspot.com), а также включает несколько дополнительно написанных разделов, расширяющих таматику рассматриваемых методов.

Репозиторий имеет следующую структуру:

* Папка `Book` содержит PDF-файл книги;
* Папка `Scripts` содержит скрипты с примерами R-кода. Каждый скрипт соответствует одной из 9 глав. Имена этих файлов состоят из `Ch_` (от _chapter_ - "глава") и порядкового `номера` главы (например, `Ch_1.R`). Кроме того, в этой папке хранится скрипт `Kendall_Theil_Regr.R`, код в котором определяет функцию для выполнения регрессионного анализа по методу Кендалла-Тейла (используется в разделе 7.3).
* Папка `Data` содержит наборы данных, используемых в книге. В частности, в ней представлены следующие файлы:

Файл | Раздел | Описание
------ | -------- | --------
`sleep_imp.Rdata` | 4.4 | Сон животных: набор данных sleep из пакета VIM после заполнения пропусков
`wader.txt` | 6.1 | Пример из работы Zuur et al. (2010) по двум видам птиц
`SparrowsElphick.txt` | 6.1 | Пример из работы Zuur et al. (2010) по воробьям
`55.45N-36.85E-TAVG-Trend.txt` | 8.1 | Среднемесячные температуры в Москве (оригинал Berkeley Earth)
`TAVG_Moscow.txt` | 8.1 | Среднемесячные температуры в Москве (преобразованные данные, 3 столбца)
`TAVG_Moscow.RData` | 8.1 | Среднемесячные температуры в Москве (данные в матричной форме)
`Гадюки.txt` | 8.3 | Данные по смертности мыше при введении яда гадюки
`dreissena_infection.txt` | 8.3 | Данные по зараженности моллюска Dreissena (сгруппированные)
`dreissena_infection_raw_data.txt` | 8.3 | Данные по зараженности моллюска Dreissena (исходные)
`Elton_TolInt.txt` | 8.4 | Соленость воды и численность видов бентоса в реках Приэльтонья
`RIKZ.txt` | 8.6 | Данные по морским животным из книги Zuur et al. (2009)
`maps.yandex.ru.JPG` | 9.1 | Карта для нанесения местообитаний гадюк
`13.txt` | 9.2 | Данные Н.Чижиковой для анализа пространственного расположения растений

С вопросами и предложениями по поводу содержания этого репозитория обращайтесь, пожалуйста, по [электронной почте](mailto:rtutorialsbook@gmail.com).