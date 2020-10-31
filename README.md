# MatmultCUDA

Все описани представлено в Notebook. 

1. CPU + PyCUDA 
https://colab.research.google.com/drive/1NOtSYGXl-Xph2jjdAqYBd38oFEp2JuN3?usp=sharing
2. Numba 
https://colab.research.google.com/drive/1LvLrk86w430oZlVNu99rE6NHUPDXbx36?usp=sharing

Ссылка на результаты работы 
https://colab.research.google.com/drive/1JmIfBNxRf3_ek14uHP5JH7p9Uszh8vOq?usp=sharing

Так как там большое количество граффиков и в git невозможно просмотреть, могут возникнуть проблемы
Поэтому приложенны ссылки.

Данные:
квадратные матрицы N на N 
где N от 100 до 2000

В данной работе представлено 4 реализации на CUDA:

1 PyCUDA

  1.1 в лоб

  1.2 с использование shared

2 Numba

  2.1 в лоб

  2.2 с использование shared

Все алгоритмы были адаптированы под любые размерности матриц, тоесть выполнялся уход от кратности.

Но при кратном количестве можно получить более выгодное время, но в данное работе это не рассматривалось.
