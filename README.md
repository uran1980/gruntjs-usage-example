<h1 align="center">Пример использования Gruntjs</h1>
<p align="center">для конкатинации и минификации css и js файлов проекта</p>

<p align="center">
  <a href="https://github.com/uran1980/web-dev-blog/blob/master/README.md">
    <img  style="max-width:100%;"
          alt="Gruntjs"
          src="https://1.gravatar.com/avatar/801a04ad77406f5ba958a607f2b27880?d=https%3A%2F%2Fidenticons.github.com%2F4e4819fe606f4444e784c9db7413ec4e.png&r=x&s=400" />
  </a>
</p>

###Интсрукция по использованию:
* Установить **[Nodejs](http://nodejs.org/)**
* Скопировать в корень проекта файлы **package.json** и **Gruntfile.js** из текущего репозитария
* Из корня проекта выполнить команду:

```
npm install
```
данная команда установить все необходимые для работы nodejs-модули прописанные в файле **package.json**
* Открыть файл **Grunfile.js** и прописать нужные пути к js и css файлам вашего проекта
* Из корня проекта выполнить команду:

```
grunt
```
Эта команда вызовет задачу с названием ```default```, которая по умолчанию запустит последовательно две задачи: конкатинацию и минификацию js и css файлов проекта.

Если требуется выполнить задачи конкатинации и минификации по отдельности, то можно выполнить эти команды
* запуск задачи конкатинации файлов проета:

```
grunt concat
```

* запуск задачи минификации файлов проекта:

```
grunt uglify
```

## Дополнительные Ссылки
* **http://gruntjs.com/getting-started**
* **https://github.com/gruntjs/grunt-contrib-uglify**
* **https://github.com/gruntjs/grunt-contrib-concat**
* **https://github.com/gruntjs/grunt-contrib-cssmin**

