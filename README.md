# toqoo
Toqoo - это todo cli приложение, которое использует обыкновенный json файл для хранения ваших задач


## Использование
**add** - добавить новую задачу.

Ключи:
   + --content/-c - задает название задачи
   + --category/-C - задает категорию
   + --deadline/-d - задает дедллайн
   + --importance/-i - задает важность задачи

**list / ls** - просмотреть список задач.
  
Что бы просмотреть только какую-то определенную категорию укажите ее в качестве аргумента: 
  
        ls <название категории>
      
**complete** - выполнить задачу. 

** После выполнения задача будет полность удалена и ее больше нельзя будет увидеть среди ваших задач.

**reImp** - изменить важность задачи.

В качестве аргументов необходимо указать id задачи и новую важность:
   
        reImp <id задачи> <новая важность>
        
 **reDead** - изменить дедлайн задачи.
 
В качестве аргументов неоходимо указать id задачи и новый дедлайн:

        reDead <id задачи> <новый дедлайн>
        
**help / --help / -h** - выводит справку о программе
