##### 1. Используя команду cat в терминале операционной системы Linux, создать
два файла Домашние животные (заполнив файл собаками, кошками,
хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
ослы, а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья человека):

```bash
	cat > HomeAnimals    
                                                                                                                                            
Cat                                                                                                                                                                          
Dog                                                                                                                                                                          
Etc.

	cat > PackAnimals

camels;
goats;
Yakov;
reindeer;

	cat PackAnimals HomeAnimals > UnityAnimals
	cat UnityAnimals
	mv UnityAnimals HumanFriends
```

##### 2. Создание директории и перемещение файла:

```bash
   mkdir dir
   mv HumanFriends dir/
```
   

##### 3. Подключение репозитория MySQL и установка пакета:
   
```bash
   wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb
   sudo apt update
   sudo apt-get install mysql-server
```

##### 4. Установка и удаление deb-пакета с помощью dpkg:

```bash   
   sudo dpkg -i /dir/mysql-apt-config_0.8.29-1_all.deb
   sudo dpkg -r /dir/mysql-apt-config_0.8.29-1_all.deb
```
   
##### 5. Вывод истории команд в терминале:

```bash
   history
```

##### 6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние 
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы:

![fg](/Diagram.png)