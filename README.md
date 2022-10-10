# Совместная работа и обновление проектов

1. Команда git fetch связывается с удалённым репозиторием и забирает из него все изменения, которых у вас пока нет и сохраняет их локально.

2. Команда git pull работает как комбинация команд git fetch и git merge, т. е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.

3. Команда git push используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий. Этой команде нужно право на запись в репозиторий, поэтому она использует аутентификацию.

4. Команда git remote служит для управления списком удалённых репозиториев.

5. Команда git archive используется для упаковки в архив указанных коммитов или всего репозитория.

6. Команда git submodule используется для управления вложенными репозиториями.

