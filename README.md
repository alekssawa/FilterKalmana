`Ярощук Александр Михайлович ИПЗ 4.04`
# FilterKalmana

# Стандартные значение

![screenshot2](screenshots/default.png)

# Q = 10

![screenshot2](screenshots/Q10.png)

# Q = 0.01

![screenshot2](screenshots/Q0_01.png)

```Как мы видим повышение параметра Q ухудшает фильтрацию, а уменьшение наоборот повышает.```

# R = 100

![screenshot2](screenshots/R100.png)

# R = 1000

![screenshot2](screenshots/R1000.png)

```Как мы видим чем больше повышаем параметр R, тем быстрее измеряется шум и тем эффективней фильтрация.```

# P = 10

![screenshot2](screenshots/P10.png)

# x = 10

![screenshot2](screenshots/X10.png)

`Указав начальную точку для фильрации x = 10, фильтрация начнется с самого начала.`

# offset = 30

![screenshot2](screenshots/Offset30.png)

`изменив offset, мы изменяем положениме сигнала по Y.`

# total_time = 2

![screenshot2](screenshots/Time2.png)

`Когда мы изменяем время вычисление волна сигнала просто изменяется, если поставим 2 то сигнал просто повторится 2 раза.`

# Лучшие параметры для фильтрации

```
frequency = 2
noise_variance = 64
R = 1000
x = 10
```

![screenshot2](screenshots/BEST_freq2_noise64_R1000_X10.png)

`Когда мы ставим такие параметры как: `

`R = 1000`

`x = 10`

`То фильрация выглядит максимально эффективно`



