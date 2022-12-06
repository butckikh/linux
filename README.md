# linux  2 dz 
 butckikh@butckikh-VirtualBox:~$ mkdir home
butckikh@butckikh-VirtualBox:~$ cd
butckikh@butckikh-VirtualBox:~$ ll
butckikh@butckikh-VirtualBox:~$ cd home
butckikh@butckikh-VirtualBox:~/home$ mkdir students
butckikh@butckikh-VirtualBox:~/home$ ll
итого 12
drwxrwxr-x  3 butckikh butckikh 4096 окт 24 23:34 ./
drwxr-x--- 23 butckikh butckikh 4096 окт 24 23:33 ../
drwxrwxr-x  2 butckikh butckikh 4096 окт 24 23:34 students/
butckikh@butckikh-VirtualBox:~/home$ cd students
butckikh@butckikh-VirtualBox:~/home/students$ touch students_list.txt
butckikh@butckikh-VirtualBox:~/home/students$ ll
итого 8
drwxrwxr-x 2 butckikh butckikh 4096 окт 24 23:35 ./
drwxrwxr-x 3 butckikh butckikh 4096 окт 24 23:34 ../
-rw-rw-r-- 1 butckikh butckikh    0 окт 24 23:35 students_list.txt
butckikh@butckikh-VirtualBox:~/home/students$ nano
butckikh@butckikh-VirtualBox:~/home/students$ nano
butckikh@butckikh-VirtualBox:~/home/students$ nano
butckikh@butckikh-VirtualBox:~/home/students$ mv /mentors_list.txt/home/students
mv: после '/mentors_list.txt/home/students' пропущен операнд, задающий целевой файл
По команде «mv --help» можно получить дополнительную информацию.
butckikh@butckikh-VirtualBox:~/home/students$ mv /mentors/mentors_list.txt/home/students
mv: после '/mentors/mentors_list.txt/home/students' пропущен операнд, задающий целевой файл
По команде «mv --help» можно получить дополнительную информацию.
butckikh@butckikh-VirtualBox:~/home/students$ mv /mentors_list.txt/home /students
mv: не удалось выполнить stat для '/mentors_list.txt/home': Нет такого файла или каталога
butckikh@butckikh-VirtualBox:~/home/students$ ll
итого 20
drwxrwxr-x 2 butckikh butckikh 4096 окт 24 23:48 ./
drwxrwxr-x 3 butckikh butckikh 4096 окт 24 23:34 ../
-rw-rw-r-- 1 butckikh butckikh   33 окт 24 23:48 mentors_list.txt
-rw-rw-r-- 1 butckikh butckikh   33 окт 24 23:48 students_list.txt
-rw-rw-r-- 1 butckikh butckikh  477 окт 24 23:47 students.txt
butckikh@butckikh-VirtualBox:~/home/students$ cd
butckikh@butckikh-VirtualBox:~$ rm mentors
rm: невозможно удалить 'mentors': Это каталог
butckikh@butckikh-VirtualBox:~$ ll
butckikh@butckikh-VirtualBox:~$ 
butckikh@butckikh-VirtualBox:~$ rm mentors -rf
Команда «home» не найдена. Возможно, вы имели в виду:
  command 'hime' from deb hime (0.9.11+dfsg-2build1)
  command 'hose' from deb netpipes (4.2-8build1)
Try: sudo apt install <deb name>
butckikh@butckikh-VirtualBox:~$ cd home
butckikh@butckikh-VirtualBox:~/home$ ll
итого 12
drwxrwxr-x  3 butckikh butckikh 4096 окт 24 23:34 ./
drwxr-x--- 22 butckikh butckikh 4096 окт 24 23:55 ../
drwxrwxr-x  2 butckikh butckikh 4096 окт 24 23:48 students/
butckikh@butckikh-VirtualBox:~/home$ cd stidents
-bash: cd: stidents: Нет такого файла или каталога
butckikh@butckikh-VirtualBox:~/home$ ll
итого 12
drwxrwxr-x  3 butckikh butckikh 4096 окт 24 23:34 ./
drwxr-x--- 22 butckikh butckikh 4096 окт 24 23:55 ../
drwxrwxr-x  2 butckikh butckikh 4096 окт 24 23:48 students/
butckikh@butckikh-VirtualBox:~/home$ ll
итого 12
drwxrwxr-x  3 butckikh butckikh 4096 окт 24 23:34 ./
drwxr-x--- 22 butckikh butckikh 4096 окт 24 23:55 ../
drwxrwxr-x  2 butckikh butckikh 4096 окт 24 23:48 students/
butckikh@butckikh-VirtualBox:~/home$ cd students
butckikh@butckikh-VirtualBox:~/home/students$ ll
итого 20
drwxrwxr-x 2 butckikh butckikh 4096 окт 24 23:48 ./
drwxrwxr-x 3 butckikh butckikh 4096 окт 24 23:34 ../
-rw-rw-r-- 1 butckikh butckikh   33 окт 24 23:48 mentors_list.txt
-rw-rw-r-- 1 butckikh butckikh   33 окт 24 23:48 students_list.txt
-rw-rw-r-- 1 butckikh butckikh  477 окт 24 23:47 students.txt
butckikh@butckikh-VirtualBox:~/home/students$ mv students students and mentors
mv: указанная цель 'mentors' не является каталогом
butckikh@butckikh-VirtualBox:~/home/students$ cd
butckikh@butckikh-VirtualBox:~$ mv students students_and_mentors
butckikh@butckikh-VirtualBox:~$ cd home
butckikh@butckikh-VirtualBox:~/home$ ll
итого 12
drwxrwxr-x  3 butckikh butckikh 4096 окт 24 23:34 ./
drwxr-x--- 22 butckikh butckikh 4096 окт 24 23:59 ../
drwxrwxr-x  2 butckikh butckikh 4096 окт 24 23:48 students/
butckikh@butckikh-VirtualBox:~/home$ mv students students_and_mentors
butckikh@butckikh-VirtualBox:~/home$ ll
итого 12
drwxrwxr-x  3 butckikh butckikh 4096 окт 24 23:59 ./
drwxr-x--- 22 butckikh butckikh 4096 окт 24 23:59 ../
drwxrwxr-x  2 butckikh butckikh 4096 окт 24 23:48 students_and_mentors/
butckikh@butckikh-VirtualBox:~/home$ cd students_and_mentors
butckikh@butckikh-VirtualBox:~/home/students_and_mentors$ ll
итого 20
drwxrwxr-x 2 butckikh butckikh 4096 окт 24 23:48 ./
drwxrwxr-x 3 butckikh butckikh 4096 окт 24 23:59 ../
-rw-rw-r-- 1 butckikh butckikh   33 окт 24 23:48 mentors_list.txt
-rw-rw-r-- 1 butckikh butckikh   33 окт 24 23:48 students_list.txt
-rw-rw-r-- 1 butckikh butckikh  477 окт 24 23:47 students.txt
butckikh@butckikh-VirtualBox:~/home/students_and_mentors$ cd
butckikh@butckikh-VirtualBox:~$ rm students_and_mentors
rm: невозможно удалить 'students_and_mentors': Это каталог
butckikh@butckikh-VirtualBox:~$ rm students_and_mentors -fr

итого 12
drwxrwxr-x  3 butckikh butckikh 4096 окт 24 23:59 ./
drwxr-x--- 21 butckikh butckikh 4096 окт 25 00:01 ../
drwxrwxr-x  2 butckikh butckikh 4096 окт 24 23:48 students_and_mentors/
butckikh@butckikh-VirtualBox:~/home$ rm students_and_mentors -fr
butckikh@butckikh-VirtualBox:~/home$ ll
итого 8
drwxrwxr-x  2 butckikh butckikh 4096 окт 25 00:01 ./
drwxr-x--- 21 butckikh butckikh 4096 окт 25 00:01 ../
butckikh@butckikh-VirtualBox:~/home$ 
