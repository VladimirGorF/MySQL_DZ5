1.	Создайте представление, в которое попадут автомобили стоимостью  до 25 000 долларов
<img width="2048" alt="Снимок экрана 2023-03-27 в 19 27 11" src="https://user-images.githubusercontent.com/110591063/228004129-dd8a11cf-81cc-4a71-9c4f-4485732e7dfc.png">

Изменить в существующем представлении порог для стоимости: пусть цена будет до 30 000 долларов (используя оператор ALTER VIEW) 
<img width="2048" alt="Снимок экрана 2023-03-27 в 19 29 26" src="https://user-images.githubusercontent.com/110591063/228004706-db53f04a-9c43-44b0-a5c9-67f68a4b7ed6.png">

Создайте представление, в котором будут только автомобили марки “Шкода” и “Ауди”
<img width="2048" alt="Снимок экрана 2023-03-27 в 19 53 47" src="https://user-images.githubusercontent.com/110591063/228011449-66f0ec8d-a9f5-4cce-85c5-e3ac5fec0b2f.png">

Добавьте новый столбец под названием «время до следующей станции». Чтобы получить это значение, мы вычитаем время станций для пар смежных станций. Мы можем вычислить это значение без использования оконной функции SQL, но это может быть очень сложно. Проще это сделать с помощью оконной функции LEAD . Эта функция сравнивает значения из одной строки со следующей строкой, чтобы получить результат. В этом случае функция сравнивает значения в столбце «время» для станции со станцией сразу после нее.
<img width="2048" alt="Снимок экрана 2023-03-28 в 11 30 38" src="https://user-images.githubusercontent.com/110591063/228177246-0174aac4-1e26-471c-a782-cad2e811ba4b.png">

Основное ДЗ в презентации, дополнительное.
Для скрипта, поставленного в прошлом уроке.
-- Получите друзей пользователя с id=
-- (решение задачи с помощью представления “друзья”)
<img width="2048" alt="Снимок экрана 2023-03-28 в 12 57 06" src="https://user-images.githubusercontent.com/110591063/228200621-4204ebd8-71e1-4775-ad47-baced3e9ac1e.png">



-- Создайте представление, в котором будут выводится все сообщения, в которых принимал 
-- участие пользователь с id = 1.

<img width="2048" alt="Снимок экрана 2023-03-28 в 13 31 06" src="https://user-images.githubusercontent.com/110591063/228208982-68e0fe22-306c-42b2-8fdd-aa73fb3f2f8a.png">
