# Ноябрь 24. Нелинейное программирование. Расчёт балки с распределённой нагрузкой (продолжение) 

### Лекция: 
- Изучите материалы
  - pdf
    - https://github.com/VetrovSV/NLST/blob/master/examples/Nonlinear%20programming%20for%20beam%20--%20regular%20method.ipynb%20-%20Colaboratory.pdf?raw=true
  - google colab  
    - https://github.com/VetrovSV/NLST/blob/master/examples/Nonlinear%20programming%20for%20beam%20--%20regular%20method.ipynb?raw=true

    
### Практическое и домашнее задание
- Добавте распеделённую нагрузку q в схему для РГР2 на горизонтальную часть рамы
  - варианты 1-6: нагрузка слева от силы F
  - варианты 1-6: нагрузка справа от силы F
-  определите q
  - задайте целевую функцию q -> max
  - F выразите через  q как: q*2
    
    
- Для запска примеров и вычислений онлайн:
  - откройте google colab
    1. меню File > Open Notebook > HitHub >
    1. Вставьте ссылку https://github.com/VetrovSV/NLST/blob/master/examples/Nonlinear%20programming%20for%20beam%20--%20regular%20method.ipynb?raw=true (распределённая нагрузка)
    1. нажмите на поиск (лупу)
    1. Откроется текст программы с вычислениями
    1. Для запуска нужно войти в аккаунт Гугл
    1. Запустите все вычисление: меню Runtime > Run All
   - Другие способы открыть файл:
    - Способ 2: Ссылка для запуска Подготовка к запуску может занять несколько минут. После подготовки появится список файлов и папок. выберете examples > далее файл LinOpt. Simplex-method.ipynb Для запуска всех вычислений: меню Cells > Run All. Аналогично открывается файл SimplexMethod for beam.ipynb
    - Способ 3: скачайте и установите Anaconda. Запустите Jupyter Notebook. Скачайте файл с вычислениями. Откройте его в Jupyter Notebook Запустите все вычисления: меню Cells > Run All


[к списку заданий](https://github.com/VetrovSV/NLST/blob/master/dist2020/tasks2020.md)
