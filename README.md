#Тестовое задание по фронтэнду
##Постановка задачи
###Общее
Приложение открывается без регистрации.
Если пользователь новый, то идет запрос signup на сервер, через который пользователь получает
сессию.
Если пользователь не новый, то должна использоваться сессия, полученная ранее (она должна
храниться в куках).
Функцию логаута реализовывать не нужно.
Когда есть сессия и идет проверка на сервере должен показываться экран с индикатором загрузки. Если
все ок то идет получение данных профиля и уже потом отображение основного экрана. Если сессия не
найдена на сервере, то идет создание новой сессии.
###Пользователь
В проекте не предусмотрено редактирование имени пользователя и аватарки.
Они генерируются на сервере.
###Проекты
По умолчанию система генерирует несколько проектов.
Новый проект добавляется нажатием на кнопке + справа от текста Projects.
Редактирование/удаление происходит через нажатие по кнопке с тремя точками (там нужно добавить
дропдаун).
Поиск осуществляется через апи (лайв).
###Таски
Новый таск создается нажатием по кнопке + в правом нижнем углу.
Таски из апи приходят списком. Визуальная их группировка должна осуществляться на фронте.
При нажатии в кружке таска, он завершается и пропадает из списка.
Нужно предусмотреть онлайн пэйджинг (при прокрутке).
##API
Описание здесь http://docs.testfrontend1.apiary.io/#
##UI
Все нужные экраны выполнены группами слоев. Размеры @2x, то есть для ретины.
##Deploy
1. Нужно сделать верстку сразу в Angular. В работе использовать AngularMaterial
2. Проект нужно разместить на github и пошарить через gh-pages так, чтобы можно было просмотреть
его YourName.github.io/RepoName
3. Подключить api
Показывать работу нужно по блокам. Сначала верстка, потом логика. Верстка +- пиксель перфект
