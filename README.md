forecast-of-a-client-leaving-the-bank

В этом проекте мы попробуем создать несколько моделей, предсказывающей останется или уйдёт клиент банка в ближайшей перспективе.

Проанализируем имеющиеся данные данные.

Попробуем ихбавиться от дисбаланса классов тремя разными способами: upsampling, downsampling, threshold change.

И на каждом протестируем на валидационной выборке несколько моделей, подобрав оптимальные параметры: линейная регрессия, решающее дерево, случайный лес. 

В итоге выберем лучшую и протестируем на тестовой выборке.
