@startuml
actor "Менеджер системы" as user
boundary "Веб-приложение" as app
entity "БД: Анкета" as data
entity "БД" as dataAll

user -> app : Ввод вопроса

activate app
loop
   app -> data: Запрос
   activate data
   
   data -> dataAll: Проверка на уникальность
   activate dataAll
   dataAll --> data: Ответ
   deactivate dataAll

   data --> app  : _Запрос обработан
   deactivate data
end
deactivate app


app -> user: Вопрос обработан
@enduml
