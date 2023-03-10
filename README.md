# DUPA - ДУПА - Виртуальная лаборатория машиностроения #

## Аннотация ##
Это приложение для ПК, которое может работать как в десктопном варианте, так и в виртуальной реальности при наличии соответствующего оборудования или без него.  

## Демонстрация ##
![демонстрация](https://github.com/LeoKhariton/Dupa/blob/main/видео%20демонстрация.gif)  
![демонстрация](https://github.com/LeoKhariton/Dupa/blob/main/демонстрация%202.gif)  
[Скачать видео](https://github.com/LeoKhariton/Dupa/blob/main/VirLab_001%202023-02-25%2021-25-47%20(online-video-cutter.com).mp4)  
## Desktop ##
### Без контроллера Leap Motion ###
Приложением можно управлять с помощью компьютерной мыши:
- менять зум (приближаться/отдаляться) можно с помощью колесика мыши
- делать облет объекта можно при зажатой правой кнопке мыши
- взаимодействовать с объектом можно при помощи правой кнопки мыши. При наведении курсора на части, с которыми можно взаимодействовать, они подсвечиваются желтым цветом.  
### С контроллером Leap Motion в режиме Desktop ###
Для контроллера необходимо включить режим "Desktop" *, т.к. обычно включается VR-режим по умолчанию.  
В этом случае можно взаимодействовать со всеми активными элементами непосредственно с помощью рук.  
**Предполагается, что пользователь уже установил **Gemini SDK для Leap Motion** и умеет ее настраивать.*
## VR ##
### Oculus Rift, Vive Focus, ... ###
Необходимо закрепить контроллер на VR-шлеме и включить режим "VR". Контроллеры-джойстики не понадобятся.  
VR-систему подключить к компьютеру.  
**Предполагается, что пользователь установил все необходимые пакеты для работы с имеющейся системой ВР.*  
### А что, если нет VR-системы? ###
В таком случае также можно постараться запустить приложение в режиме VR. Понадобится смартфон с гироскопом и гарнитура VR, которую в дальнейшем будем называть Cardboard -cb.  
*****
**Следует помнить, что использовать смартфон вместо профессиональной VR-системы может не только доставить эффект погружения, но и нежелательные последствия!**
*****
Есть несколько путей:  
1. С помощью приложений RiftCat, Trinus VR и т.д.  
Данный способ предполагает запуск компьютерных приложений в режиме виртуальной реальности на смартфоне. Однако бесплатный период длится лишь 10 минут.  
Как этим пользоваться, опускается, так как имеется масса информации (как и про подключение Leap Motion и Oculus/Vive).  
2. С помощью Unity Remote  
В данном случае нет ограничения по времени, но на компьютере должен быть установлен Unity.  
По сути, запуск приложения будет проводиться в редакторе Unity в режиме отладки (debug). Основные вычисления будет проводить компьютер. Но он будет иметь доступ к сенсорам смартфона (к камере, гироскопу, сенсорному монитору и т.д.).  
### Поддерживаемые системы ###
Windoiws, macOS, Linux
## Установка Trinus VR ##
Данное приложение разработано под носимые устройства виртуальной реальности, такие, как Oculus Rift или HTC Vive Focus.  
Они представляют собой полноценные VR-системы, включающие в себя шлем и контроллеры и могут работать как самостоятельные устройства, но чаще всего их подключают к компьютеру, который берет все вычисления на себя и использует шлем для вывода информации, как и обычный монитор - VR-шлем подключается в DP (dispaly port) компьютера и представляет собой просто наголовный монитор с двумя экранами для стереоскопического вида.  
Однако в случае, если под рукой нет специального шлема, в качестве наголовного монитора может подойти и обычный смартфон. Контроллеры не понадобятся, так как рассчитано работать с контроллером Leap Motion. Для этого необходимо установить на компьютер и смартфон специальное приложение, работающее по типу клиент-сервер.  
1. На компьютер:  
2. На мобильное устройство:  
Теперь можно использовать смартфон как "наголовный" двойной монитор.  
