# Angular
## 安装
开发环境：node 6.9.x 和 npm 3.x.x 以上的版本.
然后全局安装 Angular CLI：
```bash
$ npm install -g @angular/cli
```
## 创建项目
```bash
$ ng new my-app
```
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.1.

## 启动开发服务器
进入项目目录，并启动服务器。
```bash
ng serve --open
```
ng serve命令会启动开发服务器，监听文件变化，并在修改这些文件时重新构建此应用。

使用--open（或-o）参数可以自动打开浏览器并访问http://localhost:4200/ 。

您可以使用两个命令行选项配置开发服务器使用的默认HTTP主机和端口：
```bash
ng serve --host 0.0.0.0 --port 4201
```

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
