# Домашнее задание к лекции «Docker»

## Задание 1

- Клонируйте репозиторий командой <code>git clone https://github.com/EvilCOre88/web-hw.git</code> и перейдите в [каталог](/1.3/1) с Docker-файлом

> Для создания образа введите команду <code>docker build -t <название вашего образа (любое)> .</code>
  
> После создания можете его запускать командой <code>docker run --name <имя контейнера (любое)> -d -p 8080:80 <название образа, созданный ранее></code>.

<details>
<summary>Опции:</summary>
Порт 8080 можете поменять на любой свой, как вам будет удобно.  
</details>

- Теперь можете проверить работу контейнера перейдя на [ваш сервер](http://localhost:8080/)
  
> Для изменения стартовой страницы перейдите в [каталог](/1.3/1/my_html) с файлом index.html и измените его по своему вкусу
  
**Приятного пользования!**