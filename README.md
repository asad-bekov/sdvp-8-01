# Домашнее задание к занятию «Git»

## Задание 1

### Что нужно сделать:

1. Зарегистрируйте аккаунт на GitHub.

2. Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».

3. Склонируйте репозиторий, используя https протокол git clone ....

4. Перейдите в каталог с клоном репозитория.

![alt text](https://github.com/asad-bekov/sdvp-8-01/blob/main/images/image1.png)

5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.

![alt text](https://github.com/asad-bekov/sdvp-8-01/blob/main/images/image2.png)

6 Выполните команду git status и запомните результат.

![alt text](https://github.com/asad-bekov/sdvp-8-01/blob/main/images/image3.png)

7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.

8. Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.

9. Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.

10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.

11. Ещё раз выполните команды git diff и git diff --staged.

![alt text](https://github.com/asad-bekov/sdvp-8-01/blob/main/images/image4.png)

12. Теперь можно сделать коммит git commit -m 'images added'.

Сделайте git push origin master.

![alt text](https://github.com/asad-bekov/sdvp-8-01/blob/main/images/image5.png)

[Ссылка на коммит](https://github.com/asad-bekov/sdvp-8-01/commit/3d701d0fa1f9ec3e540fe99bcc12d5ab24dd8680)

## Задание 2
### Что нужно сделать:

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
2. Добавьте файл .gitignore в следующий коммит git add....
3. Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.

![alt text](https://github.com/asad-bekov/sdvp-8-01/blob/main/images/image6.png)

4. Сделайте коммит и пуш.

[Ссылка на коммит](https://github.com/asad-bekov/sdvp-8-01/commit/8677327bc116287cf3548470ffa1927eddc0bfd5>
