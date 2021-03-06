# 1C-TrendLine
Линия тренда в диаграмме на графике "Биржевая свеча" в 1С

Возникла задача: вывести линию тренда на биржевом графике. Попытался найти примеры решений - их нет. Одно из похожих решений https://infostart.ru/public/270236/ вообще утверждает, что стандартными способами в 1С этого сделать нельзя.

Однако, оказывается фирма 1С уже давно реализовала такую возможность https://wonderland.v8.1c.ru/blog/razvitie-diagramm/. Линия тренда появилась в релизе 8.3.10.2168.

Этот отчет демонстрирует, как можно построить диаграмму с простейшим биржевым графиком типа "свеча" и отразить на нём линию тренда. Данные для построения отчета берутся с криптобиржи https://www.binance.com/ для пары BTCUSDT, период и интервал настраиваемые.  

В отчете можно выбрать тип линии тренда и порядок аппроксимации.

При необходимости можно легко дописать функционал отображения нескольких линий тренда на одном графике. 

Отчет написан на управляемых формах, запускается только через меню Файл\Открыть. 

При запуске отчет получает информацию с биржи и выводит диаграмму. Кнопка на форме сделает тоже самое. И при любом изменении любого параметра будет повторно выведен график.

Отчет тестировался на платформе 1С:Предприятие 8.3 (8.3.10.2667) на пустой конфигурации. Теоретически будет работать на любой конфигурации в режиме управляемых форм.
