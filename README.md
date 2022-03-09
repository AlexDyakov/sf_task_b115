# Home work task B11.5

CI GitLab query on mysql-rfam-public.ebi.ac.uk

## Решение

Работает для GitLab CI/CD. Рабочий pipeline в файле .gitlab-ci.yml.

## Использование

Запрос к базе должен быть в файле query.sql. Результат работы будет направлен в вывод консоли pipeline и сохранен как артефакт со сроком жизни 1 день. Выполняется только для ветки dev!