# Documentation
***
# JustRP
**JustRP** - Плагин, добавляющий уникальную систему RolePlay для вашего сервера. Он имеет свой API и по этому поводу была написана данная документация. В ней будут рассмотрены все функции.
***
## Locker
**Locker** - Подраздел с очень лёгкой задачей, замки. Он позволяет закрывать и открывать двери при помощи ключей. Каждый ключ имеет свой уникальный идентификатор *UUID**. При исполнении команды */lockdoor*, */unlockdoor* код сравнивает *UUID* ключа с *UUID* ключа отпечатанного в записи о закрытии двери(из базы данных). В его *API* входят такие функции как
- *Класс LockedDoor. Является вспомогательным классом для удобной работы с базой данных. Конструктор принимает данные аргументы Block block и UUID uuid.*
