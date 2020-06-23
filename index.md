&<!DOCTYPE html><html><head><meta charset="utf-8"><title>Documentation.md</title><style></style></head><body id="preview">
<h1 class="code-line" data-line-start=0 data-line-end=1><a id="Documentation_0"></a>Documentation</h1>
<hr>
<h1 class="code-line" data-line-start=2 data-line-end=3><a id="JustRP_2"></a>JustRP</h1>
<p class="has-line-data" data-line-start="3" data-line-end="4"><strong>JustRP</strong> - Плагин, добавляющий уникальную систему RolePlay для вашего сервера. Он имеет свой API и по этому поводу была написана данная документация. В ней будут рассмотрены все функции.</p>
<hr>
<h2 class="code-line" data-line-start=5 data-line-end=6><a id="Locker_5"></a>Locker</h2>
<p class="has-line-data" data-line-start="6" data-line-end="7"><strong>Locker</strong> - Подраздел с очень лёгкой задачей, замки. Он позволяет закрывать и открывать двери при помощи ключей. Каждый ключ имеет свой уникальный идентификатор <em>UUID</em>*. При исполнении команды <em>/lockdoor</em>, <em>/unlockdoor</em> код сравнивает <em>UUID</em> ключа с <em>UUID</em> ключа отпечатанного в записи о закрытии двери(из базы данных). В его <em>API</em> входят такие функции как</p>
<ul>
<li class="has-line-data" data-line-start="7" data-line-end="8"><em>Класс LockedDoor. Является вспомогательным классом для удобной работы с базой данных. Конструктор принимает данные аргументы Block block и UUID uuid.</em></li>
</ul>
</body></html>
