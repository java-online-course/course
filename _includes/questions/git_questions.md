### Version Control System
1. Для чего необходима система контроля версий (VCS)? Чем она полезна? Какие бывают виды VCS?
1. Что такое Git? Есть ли альтернативы?
1. В чем отличие рабочей директории (working directory), локального репозитория (local repository) и центрального 
репозитория (central repository)?

### Git - Commands
1. Что такое commit?
1. Что такое branch? Для чего он нужен?
1. Что такое merge?
1. Что такое tag? Для чего они нужны?
1. Что такое rebase? Для чего его применяют?
1. Что такое revert?
1. Что такое reset?
1. Что такое stash? Чем он полезен?
1. Что такое cherry-pick? Чем он полезен?
1. Что такое Head?
1. Как объединить два бранча? Что будет результатом?
1. Что такое merge-conflict? Почему они возникают? Как их решить?
1. Что такое репозиторий?
1. Что такое pull\push? Что такое pull-request (merge-request)?

### Git - Cases
1. Что такое git flow? Расскажите, как вы его понимаете? Опишите по шагам весь процесс. Для чего нужны master и develop ветки?
1. Вам необходимо избежать попадания файлов вида *.class в центральный репозиторий из рабочей директории, что будете делать?
1. Вы сделали объемные изменения в множестве файлов, сделали коммит и запушили его в центральный репозиторий. Тут же вы поняли, что это изменение некорректно и его не должно быть в коде. Что будете делать?
1. Вы сделали несколько новых коммитов в локальном репозиторий. Ваш коллега в это время запушил в центральный репозиторий в эту же ветку несколько своих коммитов (изменения в других файлах).
Вы хотите запушить свои изменения в центральный репозиторий. Сможете ли вы это сделать? Ваши действия?
1. Вы с коллегой поменяли один и тот же файл, одни и те же строки (изменили логику работы одного и того же функционала). 
Как объединить изменения в Git? Как разрешить конфликт слияния? Как определить, чей вариант изменений должен остаться в репозитории?
1. Вы с коллегой поменяли один и тот же java-файл, но разные методы. При этом вы работали в ветке SUPER-FEATURE-А, а коллега в ветке SUPER-FEATURE-В. У вас и у него после изменений программа работает корректно. 
После этого вы замержили ветку коллеги в свою (при мерже конфликтов не возникло). Говорит ли отсутствие конфликтов слияния о работоспособности получившегося результата программы?
