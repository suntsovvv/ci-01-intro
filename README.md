# Домашнее задание к занятию 7 «Жизненный цикл ПО»
Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:
1. Open -> On reproduce.
2. On reproduce -> Open, Done reproduce.
3. Done reproduce -> On fix.
4. On fix -> On reproduce, Done fix.
5. Done fix -> On test.
6. On test -> On fix, Done.
7. Done -> Closed, Open.

![image](https://github.com/suntsovvv/ci-01-intro/assets/154943765/90e2de19-5497-4f61-bea2-27aa4254786a)

Остальные задачи должны проходить по упрощённому workflow:

1. Open -> On develop.
2. On develop -> Open, Done develop.
3. Done develop -> On test.
4. On test -> On develop, Done.
5. Done -> Closed, Open.

![image](https://github.com/suntsovvv/ci-01-intro/assets/154943765/83dadc30-f9ca-4361-b216-51dfea28e3f7)   



   
