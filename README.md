На структуре модели изображен сервер с размещенным гипервизором, на ко-
тором установлено несколько виртуальных машин, выполняющих определенные
задачи управления.
В исследуемом варианте построения системы используются четыре вирту-
альные машины:
 виртуальная машина ВМ1 управляет доступом к интернет. Она может
предоставлять беспроводной доступ к интернет с различными настройка-
ми. Например, можно организовать две Wi-Fi сети, одна из которых пред-
назначена для детей, с установленными фильтрами, которые перекрывают
доступ к определенному контенту, вторая сеть предназначена для родите-
лей и фильтры могут отсутствовать;
 виртуальная машина ВМ2 является сервером видео наблюдения. На ней
работают системы видеокамер, установленные в доме и на территории во-
круг дома, где могут храниться записи с камеры, также она может предос-
тавлять удаленный доступ к камерам;
 виртуальная машина ВМ3 служит сервером для различных датчиков.
К ней подключаются датчики, которые установлены по всему дому. Дан-
ный сервер может обеспечивать единый контроль всех датчиков, вести
мониторинг и предоставлять возможность настройки датчиков;
 виртуальная машина ВМ4 служит сервером резервного копирования.
В задачу ВМ4 входит создание резервных копий всех виртуальных машин,
установленных на сервере.
После создания резервных копий ВМ4 отправляет их в сетевое хранилище.
В случае сбоя или выхода из строя одной или нескольких виртуальных машин с
помощью данного сервера их можно легко восстановить из копий [3]. Данный сер-
вер может быть настроен на мониторинг всех важных системных файлов и, в слу-
чае их повреждения, программа автоматически заменит поврежденные файлы и
перезагрузит систему. Связь сервера с сетевым хранилищем обеспечивает мар-
шрутизатор, который также может обеспечивать главный сервер подключением к
сети интернет. 
