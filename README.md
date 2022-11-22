# HSE-CacheDecorator
🏫 Homework at the university

Текст задания:

1. Напишите декоратор, который может:

- Поддерживать кэш размера N из обработанных входных значений. Попробуйте реализовать два варианта кэша по следующей логике:

  1. храним в памяти результат работы функции для N самых часто используемых входных параметров 
  В таком случае, если кэш на текущий момент заполнен и на вход пришел новый набор параметров, нужно освободить самый непопулярный набор параметров из имеющихся в кэше и заменить его тем, который пришел на вход.

  2. храним в памяти результат работы для N последних входных параметров
  Переключение между вариантами сделайти в виде отдельного параметра (например, назовите его cache_type)

  Если N=-1, то размер кэша считаем "бесконечным". Если N=None (по дефолту), то кэш считается отключенным и ничего хранить не надо.

- хранить небольшую историю последних вызовов размера K и печатать ее после каждого нового выполнения функции. В случае, если K = None (по дефолту), историю хранить не нужно.

2. Продемонстрируйте на каких-нибудь примерах, что ваши реализации кэшей действительно работают
