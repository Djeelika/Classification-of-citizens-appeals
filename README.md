# Classification-of-citizens-appeals
Классификация обращений граждан.
Цифровой прорыв. Региональный Чемпионат, Курская область https://hacks-ai.ru/championships/758244
-------------------------------------------------------------
Данную сеть создавала сама. 
Краткое описание решения на Bag-of-words: 
На первом шаге 5 блоков с полносвязными сетями с разными активационными функциями.
На втором шаге конкотенация всех блоков
На третьем шаге отработка всех фичей из общих 5 блоков.

Технические особенности: 
Python, tensorflow.keras, pymorphy2, nltk, numpy, pandas, pickle, sklearn.preprocessing

Уникальность: 
Построенный алгоритм даже не искала в интернете, в научных публикациях.
Данную сеть создавала сама.


------------------------------------------------------------------
В связи со сложной структурой и нелинейными зонами ответственности в органах исполнительной и государственной власти, а также из-за большого потока входящих сообщений разной направленности возникают сложности с оперативной маршрутизацией сообщений непосредственным исполнителям. Сообщение гражданина проходит длинную цепочку передачи «из рук в руки», что существенно уменьшает время, отведенное на непосредственное устранение причин возникновения проблемы. А также растущая популярность платформ обратной связи увеличивает нагрузку на модераторов и приводит к росту штата персонала, обслуживающего работу порталов.

Участникам чемпионата предлагается разработать классификатор для автоматического определения категории запроса по тексту сообщения, оставленному на сайте Администрации Курской области.

Создание такого алгоритма позволит сократить время ответа на обращения жителей, так как существенно сократится время на предобработку и маршрутизацию обращений.
