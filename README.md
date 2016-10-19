# OOAD-WEEK09
##Class Diagram

###ภาพที่ 1 taxi 
###code
  ```
  @startuml
  class taxi
  taxi *-- taxidriver 
  taxi o--  customer
  taxi *-- taximeters
  @enduml
  ```
####![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLYX9hCZauWAH2bgwkc1kIb5cMMgH0aGm7oYea5nQN9AVcrg4gYutjIIrg9YBYyiXDIy5Q280)

#####ภาพที่ 2 ส่วนประกอบของรถ
```
@startuml
class Car
Car *- Wheel : have 4 >
Car *-- engine
Car -- door
Car -- driver
@enduml
```
#####![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLd1EBEBYuWAI2bgw2k4PgQav2bOA6ObbgGec2dPGSLs5rBpqpBnKC1V8IydFBuApYpBBKeku75BpKe260W00)

######ภาพที่ 3
```
@startuml
class  name {
 ~firstname
 ~lastname
 ~age
 #id
 ~name()
 #birthday()
}
@enduml
```
######![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLb38IynDLQZcKgXBoomgBW7nW6oW58oPc0uabJDJW4oGY8Oca9UKMLIIaP9O2UJKSZcavgK0pGC0)

######ภาพที่ 4  
```
@startuml
class class
class -- student
class -- teacher
class *-- Desk 
class *-- chair
class *-- blackboard
@enduml 
```

######![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLW2JN5nGdgwkGd59QKfgNWb2e2GrCJaZjGYcH0iev99QdAs0n4_EICmiGk8dvIGcPoVb9nQbS74vfEQb0Aq30000)

######ภาพที่ 5 
```
@startuml
class  name {
 ~name
 #id
 ~name()
}
@enduml
```
######![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU9ApaaiBbPGo4lCJLMevbAe0p6u59GpKw1i3KqkhbekBeVKl1IWUW00)

