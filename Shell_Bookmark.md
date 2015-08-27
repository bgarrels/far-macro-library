#summary Закладки в панелях (c) Max Rusov

  * [Shell Macros](Shell.md)

### Описание ###

> Набор макросов для быстрой установки закладок в панелях и перехода к ним. Позволяет устанавливать произвольное количество закладок, благодаря тому что закладки могут иметь многобуквенные мнемоники. Для установки закладки удерживайте RCtrlShift и набирайте ее мнемонику, для перехода к закладке - удерживайте RCtrl. Действие происходит в момент отпускания префиксных клавиш.

> Также имеется меню со списком всех назначенных закладок (по умолчанию **Ctrl+/**). При выборе закладки происходит переход в каталог. Для редактирования или удаления закладки ее надо выделить в меню (Ins) и нажать Enter.

> Поддерживаются плагинные панели (для некоторых плагинов, например - RegEditor)

  1. **RCtrlShift**+_Буквы или цифры_ - Установить закладку
  1. **RCtrl**+_Буквы или цифры_ - Перейти к закладке
  1. **Ctrl+/** - Меню закладок

> Основано на идее Kerberos464<br>
<blockquote><a href='http://forum.farmanager.com/viewtopic.php?f=15&t=6137'>http://forum.farmanager.com/viewtopic.php?f=15&amp;t=6137</a></blockquote>


<h3>Текст</h3>

<ul><li><a href='http://far-macro-library.googlecode.com/svn/trunk/Shell/Bookmark.fml'>Download FML</a></li></ul>

<ul><li><a href='http://far-macro-library.googlecode.com/svn/trunk/Shell/Bookmark.v2.fml'>Download FML v2</a></li></ul>

<ul><li><a href='http://far-macro-library.googlecode.com/svn/trunk/Shell/Bookmark.fmlua'>Download FMLUA v4</a></li></ul>

<h3>Изменения</h3>
<h4>Shell Bookmark v2</h4>

<ul><li>Меню закладок отображает все закладки с любой длинной мнемоники<br>
</li><li>В путях могут использоваться переменные окружения<br>
</li><li>Макрос не мешает работе стандартных закладок Far (если они не перекрыты закладками макроса)<br>
</li><li>Требуется Far 3 build 2576+, MacroLib v 1.0.17</li></ul>

<h4>Shell Bookmark v3</h4>

<ul><li>LUA Версия (Требуется Far 3 build 2851+, MacroLib v 1.0.19+)</li></ul>

<h4>Shell Bookmark v4</h4>

<ul><li>Оптимизированная LUA Версия (Требуется MacroLib v 1.0.20+)