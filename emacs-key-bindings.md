# Emacs key bindings

`C` = `Ctrl`  
`M` = `Alt`  

## Misc keys
Quit Emacs: `C-x  C-c`  
Quit a command: `C-g`  
Undo: `C-/` (or `C-_`, or `C-x u`)  
Numeric argument (repeat count): `C-u digits key` or `M-digits key`  
Example: `C-u 10 C-n` (move cursor 10 lines down), `C-u 10 C-v` (scroll 10 lines down)

## Cursor (point) movements
Description | Key
----- | -----
Next char | `C-f`
Prev char | `C-b`
Next word | `M-f`
Prev. word | `M-b`
Next line | `C-n`
Prev. line | `C-p`
Start of line | `C-a`
End of line | `C-e`
Start of sentence | `M-a`
End of sentence | `M-e`

## Scrolling
Description | Key
----- | ------
Scroll up | `C-v`
Scroll down | `M-v`
Start of buffer (text) | `M-<` (Alt-Shift-<)
End of buffer (text) | `M->` (Alt-Shift->)
Move current line to the center, top, bottom of the screen | `C-l` (repeat 1-3 times)
Scroll 10 lines down | `C-u 10 C-v`
Scroll 10 lines up | `C-u 10 M-v`

## Inserting and deleting
Description | Key
----- | ------
Delete prev. char. | `Bksp`
Delete next char. | `C-d`
Kill prev. word | `M-Bksp`
Kill the next word | `M-d`
Kill a line | `C-a`, `C-k`
Kill several lines | `C-a`, `C-u <число> C-k`
Kill from the cursor position to end of line | `C-k`
Kill to the end of the current sentence | `M-k`
Set a mark | `C-Space`
Kill (cut) the region (selected text) | `C-w`
Copy region | `M-w`
Вставить удаленный текст | `C-y` (yanking)
Вставить другой текст | `M-y` (также с `C-u <число>`, число может быть отрицательным)

## Окна
Описание | Команда
----- | ------
Развернуть окно (одно окно, закрыть другие окна) | `C-x 1`
Закрыть окно | `C-x 0`
Переключиться на другое окно | `C-x o` (other)
Разделить окно по-горизонтали | `C-x 2`

## Файлы / буфера
Описание | Команда
----- | ------
Открыть (найти) файл | `C-x C-f`
Сохранить | `C-x C-s`
Список буферов | `C-x C-b`
Переключиться на буфер | `C-x b`
Сохранить некоторые буфера | `C-x s`

## Справка
Описание | Команда
----- | ------
Показать команду, привязанную к сочетанию | `C-h c <сочетание клавиш>`
Показать справку по команде, привязанной к сочетанию | `C-h k <сочетание клавиш>`
Описание функции | `C-h f`
Поиск команды/функции | `C-h a <ключевое слово>`
