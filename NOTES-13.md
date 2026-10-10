## Варіант
Журнал 16, варіант 6, Захаренко Сергій

## 1. stash list
Saved working directory and index state WIP on lab3/variant-6-Zakharenko: f16b015 fix typo

## 2. cherry-pick
d72ff3b (feature/pick-6) оновити статус роботи
ac1e3c9 (origin/main, origin/HEAD) HEAD@{13}: checkout: moving from main to feature/pick-6



## 3. reflog
32121ff (tag: v0.1-Zakharenko, recover/v6) HEAD@{7}: checkout: moving from lab3/variant-6-Zakharenko to v0.1-Zakharenko
32121ff (tag: v0.1-Zakharenko, recover/v6) HEAD@{8}: commit: Зіпсувати рядок
482f2da HEAD@{9}: commit (amend): Уточнити статус, варіант 6
d72ff3b (feature/pick-6) HEAD@{10}: reset: moving to d72ff3b4ba0e2f29d2442c82d2e6d8733a459cf5
d72ff3b (feature/pick-6) HEAD@{11}: checkout: moving from feature/pick-6 to lab3/variant-6-Zakharenko

## 4. revert
f16b015 (HEAD -> lab3/variant-6-Zakharenko, origin/lab3/variant-6-Zakharenko) fix typo
b125a4c WIP: чернетка
32121ff (tag: v0.1-Zakharenko, recover/v6) Зіпсувати рядок
482f2da Уточнити статус, варіант 6
ac1e3c9 (origin/main, origin/HEAD) Add STATUS.md file
1873032 Initial commit

## 5. тег
commit f16b015b7e097b144994302339c5f321ebc25797 (HEAD -> lab3/variant-6-Zakharenko, origin/lab3/variant-6-Zakharenko)
Author: Захаренко Сергій <parkydarky353@gmail.com>
Date:   Sat Oct 10 21:27:58 2026 +0200

    fix typo

diff --git a/STATUS.md b/STATUS.md
index 2236074..eb726fa 100644
--- a/STATUS.md
+++ b/STATUS.md
@@ -3,4 +3,5 @@
 2. основа
 3. середина
 Статус: на рев'ю (lab3-v6)
-WIP
\ No newline at end of file
+WIP
+fix

## 6. rebase -i
pick b125a4c WIP: чернетка
squash f16b015 fix typo

## 7. blame
482f2dae (Захаренко Сергій 2026-10-10 13:25:38 +0200 1) Статус: на рев'ю (lab3-v6)



## 8. fork
origin — мій форк (мій репозиторій на GitHub), upstream — оригінал.
Беру нові зміни оригіналу: git fetch upstream.
Свої зміни пушу в origin.
Pull request відкриваю в upstream/main.