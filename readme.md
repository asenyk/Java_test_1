<p>Уровень 1</p>
В университете читаются семинары. Каждый семинар ведёт один профессор, при этом профессор может вести более чем один семинар. Студенты могут подписываться на семинары, каждый студент может быть подписан на несколько семинаров, и семинар может посещать несколько  студентов. Семинар может быть активным или неактивным, активным он может быть только если на него подписан хотя бы один студент.  Участие студента в семинаре стоит определённую сумму денег.

Требуется приложение, удовлетворяющее таким функциональным требованиям:

    обеспечивается создание, редактирование (включительно с состоянием) и удаление семинаров
    обеспечивается поиск семинара по имени
    обеспечивается создание, редактирование и удаление преподавателей
    поиск преподавателей по имени и фамилии
    обеспечивается создание, редактирование и удаление студентов
    поиск студентов по имени и фамилии
    обеспечивается просмотр списка семинаров для преподавателя, назначение преподавателя на семинар и снятие его с семинара
    обеспечивается просмотр списка семинаров для студента, подписывание студента на семинар и отписывание от семинара
    расчёт общей суммы, которую студент должен заплатить за участие во всех выбранных семинарах. По умолчанию это простая сумма, но при участии в 5 и более семинарах студенту предоставляется скидка 10%

Системные  требования

    в качестве сервера базы данных используется MySQL, в которой хранятся данные о семинарах, студентах, и преподавателях
    пользователи взаимодействуют с приложением через web-интерфейс, построенный на одной из следующих технологий:
    JSF
    Spring MVC
    Plain JSP

Для доступа к базе данных используется одна из следующих технологий:

    JPA
    Hibernate
    Прямые вызовы JDBC

Приложение должно работать в одном из следующих контейнеров:

    Jboss 7.1
    Tomcat 6.0