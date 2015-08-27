﻿#summary Быстрая фильтрация в панелях (c) Max Rusov

  * [Shell Macros](Shell.md)

### Описание ###

> Набор макросов для быстрой фильтрации в панелях. Все действия выполняются при нажатии RAlt. Возможности:

  1. **RAlt**+_Буквы или цифры_ — Фильтрация, добавить символ к фильтру
  1. **RAlt+BS** — Удалить символ из фильтра
  1. **RAlt+/** — Редактировать фильтр в диалоге
  1. **RAlt+-** — Включить/выключить режим исключающего фильтра
  1. **RAlt+\** — Включить/выключить режим фильтрации каталогов
  1. **RAlt** — Удалить весь фильтр

> Внимание: Макрос (до версии v4 включительно) рассчитан на английский язык интерфейса FAR. Для других языков требуется доработка напильником.


### Текст ###

  * [Загрузить FML](http://far-macro-library.googlecode.com/svn/trunk/Shell/FastFilter.fml)
  * [Загрузить FML v2](http://far-macro-library.googlecode.com/svn/trunk/Shell/FastFilter.v2.fml)
  * [Загрузить FML v3](http://far-macro-library.googlecode.com/svn/trunk/Shell/FastFilter.v3.fml)
  * [Загрузить FML v4](http://far-macro-library.googlecode.com/svn/trunk/Shell/FastFilter.v4.fml)
  * [Загрузить FML v5](http://far-macro-library.googlecode.com/svn/trunk/Shell/FastFilter.v5.fml)
  * [Загрузить FMLUA v6](http://far-macro-library.googlecode.com/svn/trunk/Shell/FastFilter.fmlua)

### Изменения ###

#### 110204 Maximus5 (v2) ####
  * одновременно фильтруется по двум языкам через xlat
  * курсор сдвигается не первый найденный элемент, если до фильтрации был на ".."
  * запоминается (и восстанавливается) режим 'Toggle folder filter'

#### 110216 Maximus5 (v3) ####
  * при нажатии Enter, после выполнения (вход в папку, запуск файла,...) фильтр сбрасывается

#### 110501 Maximus5 (v4) ####
  * FastFilterClear не только убирает свой фильтр, но если его нет - то снимает любой фильтр на панели
  * Обработка букв "БЮХЪЖЭЁ"

#### 110721 Maximus5 (v5) ####
  * раздельная обработка быстрых фильтров на правой и левой панелях
  * для ускорения ввода (особенно на сетевых дисках) фильтр применяется только при RAlt:Up
  * во время ввода фильтра он "печатается" к ком.строке
  * во время ввода фильтра RAltBS удаляет последний введенный символ
  * однократное нажатие RAlt открывает QSearch с введенным "**"**

#### Fast Filter v6 ####

  * LUA Версия (Требуется Far 3 build 2851+, MacroLib v 1.0.20+)