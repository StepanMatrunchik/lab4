# Тест-кейсы

---

#### Веб-сайт: [myglo](https://www.myglo.ru)

---

### 1. **Добавление товара в корзину**

#### **Предусловие: Наличие интернет-соединения.**

##### 1.1 В верхней панели навестись на "Каталог".

##### 1.2 В выдвигающемся списке кликнуть на "Устройства".

##### 1.3 Немного пролистать страницу вниз и кликнуть на кнопку "Добавить в корзину" под одним из товаров.

#### **Ожидаемый результат: Появится окно, информирующее нас о том, что товар добавлен в корзину.**

---

### 2. **Удаление товара из корзины**

#### **Предусловие: Наличие интернет-соединения, наличие хотя-бы одного товара в корзине.**

##### 2.1 В верхней панели кликнуть на иконку ![корзины](bag.png) .

##### 2.2 Кликнуть на крестик напротив названия товара, который мы хотим удалить из корзины.

##### 2.3 В появившемся окне подтвердить удаление товара из корзины, кликнув на кнопку "ДА, УДАЛИТЬ".

#### **Ожидаемый результат: Товар удален из корзины.**

---

### 3. **Добавление в корзину больее одного товара**

#### **Предусловие: Наличие интернет-соединения, открыта вкладка [перечня товаров](https://shop.myglo.by/catalog/)**

##### 3.1 Изменить количество товара на 4.

##### 3.2 Нажать на кнопку "В КОРЗИНУ".

#### **Ожидаемый результат: В корзине находятся 4 товара**

---

### 4. **Вписать количество товара, больше чем 999**

#### **Предусловие: Наличие интернет-соединения, открыта вкладка [перечня товаров](https://shop.myglo.by/catalog/)**

##### 4.1 Изменить количество товара на 1000.

##### 4.2 Нажать на Enter.

#### **Ожидаемый результат: Количество товаров изменится на максимально допустимое и появится предупреждение о том что максимальное количество товаров - 999.**

---

### 5. **Добавить в корзину более одного товара со страницы товара**

#### **Предусловие: Наличие интернет-соединения, открыта вкладка [товара](https://shop.myglo.by/catalog/glo-hyper-x2-belo-zolotoy/).**

##### 5.1 Изменить количество товара на 4.

##### 5.2 Нажать на кнопку "В КОРЗИНУ".

#### **Ожидаемый результат: В корзине находятся 4 товара.**
#### **НО: В корзине находится 1 товар.**

---

### 6. **Вписать количество товара, больше чем 10 со страницы товара**

#### **Предусловие: Наличие интернет-соединения, открыта вкладка [товара](https://shop.myglo.by/catalog/glo-hyper-x2-belo-zolotoy/).**

##### 6.1 Изменить количество товара на 11.

##### 6.2 Нажать на Enter.

#### **Ожидаемый результат: Количество товаров изменится на максимально допустимое и появится предупреждение о том что максимальное количество товаров - 10.**

---

### 7. **Увеличить количество товаров через "+"**

#### **Предусловие: Наличие интернет-соединения, открыта вкладка [товара](https://shop.myglo.by/catalog/glo-hyper-x2-belo-zolotoy/).**

##### 7.1 Ввести количество товара равное 4.

##### 7.2 Нажать на "+".

#### **Ожидаемый результат: Количество товаров станет равным 5.**
#### **НО: Количество товаров станет равным 6.**

---

### 8. **Уменьшить количество товаров через "-"**

#### **Предусловие: Наличие интернет-соединения, открыта вкладка [товара](https://shop.myglo.by/catalog/glo-hyper-x2-belo-zolotoy/).**

##### 7.1 Ввести количество товара равное 4.

##### 7.2 Нажать на "-".

#### **Ожидаемый результат: Количество товаров станет равным 3.**
#### **НО: Количество товаров станет равным 2.**

---

### 9. **Изменение цвета боковой панели товара**

#### **Предусловие: Наличие интернет-соединения, открыта вкладка [товара](https://shop.myglo.by/catalog/glo-hyper-uniq-black/).**

##### 9.1 Выбрать красный цвет боковой панели, нажав на кружочек с соответственным цветом.

#### **Ожидаемый результат: Начнется анимация смены цвета боковой панели на картинке товара.**

---

### 10. **Поиск магазинов, в которых имеется в наличии определенный товар**

#### **Предусловие: Наличие интернет-соединения, открыта вкладка [поиска магазинов](https://myglo.by/map/).**

##### 10.1 Пролистать страницу вниз до карты .

##### 10.2 Выбрать нужный товар и тип магазина.

#### **Ожидаемый результат: На карте отобразятся все магазины подходящие под заданные критерии.**

---
