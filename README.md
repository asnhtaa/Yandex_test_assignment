# Тестовое задание на вакансию "Стажер тестировщик" в Yandex

## Задание
Напишите тест-кейсы, необходимые и достаточные для полной проверки колдунщика онлайн-перевода, который появляется по запросу ["переводчик онлайн"](https://www.yandex.ru/search/?text=%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%D0%B4%D1%87%D0%B8%D0%BA%20%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD&lr=213), ограничиваясь только страницей выдачи по этому запросу.
***

## Решение

### UI-тестирование:

* Test_case_001
  
Проверка наличия поля ввода текста для перевода, там отображается текст «Введите текст»
* Test_case_002

Проверка наличия и функциональности кнопки «Очистить» 
* Test_case_003

Проверка наличия списка для выбора исходного и целевого языков перевода
* Test_case_004

Проверка выбора исходного и целевого языка перевода
* Test_case_005

Проверка ввода данных из буфера обмена (CTRL+C, CTRL+V)
* Test_case_006

Проверка наличия и функциональности кнопки «Вставить текст»
* Test_case_007

Проверка наличия и функциональности кнопки «Копировать» полученный результат
* Test_case_008

Проверка функциональности озвучки перевода
* Test_case_009

Проверка функциональности озвучки введенного текста 
* Test_case_010

Проверка обработки тегов
* Test_case_011

Проверка наличия и функциональности кнопки, показывающей, откуда цитата в разделе «Примеры»
* Test_case_012

Проверка наличия и функциональности кнопки «Обратный перевод», которая позволяет поменять исходный и целевой языки местами


### Функциональное тестирование:

* Test_case_013


Проверка точности перевода, включая перевод на не очень распространенные языки (например, датский)
* Test_case_014

Проверка автоматического распознавания исходного языка
* Test_case_015

Проверка точности перевода при установлении неправильного исходного языка перевода
* Test_case_016

Проверка качества распознавания речи на различных языках
* Test_case_017

Проверка обработки специальных символов, цифр
* Test_case_018

Проверка обработки максимального и минимального количества символов (введение количества символов, равных лимиту, лимит-1 символ, лимит+1 символ)
* Test_case_019

Проверка ввода пробелов перед текстом (они должны обрезаться)
* Test_case_020

Проверка точности перевода различных типов текстов (обычный текст, сложные грамматические конструкции, фразеологизмы, специальные термины).
* Test_case_021

Проверка правильности синонимов в разделе словарь 
* Test_case_022

Проверка правильности примеров, в разделе «Примеры»


### Тестирование производительности:

* Test_case_023

Проверка стабильности работы переводчика при высокой нагрузке
* Test_case_024

Проверка скорости работы переводчика при высокой нагрузке
* Test_case_025

Проверка стабильности работы переводчика при смене запроса во время загрузки перевода
* Test_case_026

Проверка стабильности работы переводчика в случае если исходный и целевой язык поменяются во время загрузки перевода


### Тестирование безопасности:

* Test_case_027

Проверка сохранения конфиденциальности введенной пользователем информации


### Тестирование совместимости:

* Test_case_028

Проверка работоспособности переводчика на различных операционных системах (Windows, macOS, Linux) 
* Test_case_029

Проверка работоспособности переводчика в различных браузерах (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, Яндекс.Браузер и др.)
* Test_case_030

Проверка работоспособности переводчика на мобильных устройствах (iOS, Android)