<h1 align="center">Пример использования Gruntjs</h1>
<p align="center">для конкатинации и минификации css и js файлов проекта</p>

<p align="center">
  <a target="_blank" href="http://gruntjs.com/getting-started">
    <img  style="max-width:100%;"
          alt="Gruntjs"
          height="200px"
          src="https://1.gravatar.com/avatar/801a04ad77406f5ba958a607f2b27880?d=https%3A%2F%2Fidenticons.github.com%2F4e4819fe606f4444e784c9db7413ec4e.png&r=x&s=400" />
  </a>
</p>

###Интсрукция по использованию:
* Установить **[Nodejs](http://nodejs.org/)**.
* Установить nodejs-модуль **grunt-cli**:

```
npm install -g grunt-cli
```

* Скопировать в корень проекта файлы **[package.json](https://github.com/uran1980/gruntjs-usage-example/blob/master/package.json)** и **[Gruntfile.js](https://github.com/uran1980/gruntjs-usage-example/blob/master/Gruntfile.js)** из текущего репозитария
* Из корня проекта выполнить команду:

```
npm install
```
данная команда создаст в корне проекта каталог ```node_modules``` и установит в него все необходимые для работы nodejs-модули прописанные в файле **[package.json](https://github.com/uran1980/gruntjs-usage-example/blob/master/package.json)**.
* Открыть файл **[Grunfile.js](https://github.com/uran1980/gruntjs-usage-example/blob/master/Gruntfile.js)** и прописать нужные пути к js и css файлам вашего проекта
* Из корня проекта выполнить команду:

```
grunt
```
Эта команда вызовет задачу с названием ```default```, которая по умолчанию запустит последовательно три подзадачи (**concat**, **uglify** и **cssmin**). В итоге мы получим объединенные и сжатые js и css файлы для проекта.

Если требуется выполнить задачи конкатинации и минификации по отдельности, то можно выполнить эти команды
* запуск задачи конкатинации js файлов проета:

```
grunt concat
```

* запуск задачи минификации js файлов проекта:

```
grunt uglify
```

* запуск задачи конкатинации и минификации css файлов проекта:

```
grunt cssmin
```

## Дополнительные Ссылки
* **http://gruntjs.com/getting-started**
* **https://github.com/gruntjs/grunt-contrib-uglify**
* **https://github.com/gruntjs/grunt-contrib-concat**
* **https://github.com/gruntjs/grunt-contrib-cssmin**

