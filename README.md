<H1>Тестовое задание Groozgo</H1>

<h3>
    Проект Yii2<br>
    Миграции база MySQL<br>
</h3>

<h5>
    Должна быть таблица пользователей<br>
    Должна быть таблица адресов пользователей (причем их может быть множесво "один ко многим")<br>
</h5>
<h5>
<div>
    <p>Таблицы для хранения данных:</p>
    <code>
        <b>user</b><br>
        <div>
             id(int(11) autoincrement)<br>
             name(strign(255)) (), <br>
             surname(string(255), <br>
             birth (date), <br>
             sex (int()),<br>
             phone_number(string(255))<br>
        </div>
        <br>
        <b>address</b><br>
        <div>
            id(int(11) autoincrement)<br>
            address (text) <br>
         </div>
        <br>
        <b>user_address</b><br>
        <div>
            id(int(11) autoincrement)<br>
            user_id(int(11)) - ID пользователя<br>
            address_id (int(11)) - ID адресса <br>
        </div>
    </code>
</div>
</h5>

Сделать страницу отображения списка пользователей и форма редактирования пользователя:
Поля дата рождения и номер телефона должны иметь соответствующие форматы ('dd.mm.Y', '+7 (777) 777-7777'), формат должен валидироваться JS без использования доп. библиотек и фреймворков (jQuery можно).

На странице редактирования пользователя разместить форму добавления, редактирования адресов пользователя и отображение добавленных адресов.
Подсказки в поле Адрес, используя API Yandex или Google.

Детализация адреса по полям не нужна
Допускается ajax, но желательны еще маски на полях

<h5>
<p><b>В итоге мы должны получить:</b></p>
<ul>
    <li>страница со списком пользователей</li>
    <li>форма добавления нового пользователя</li>
    <li>форма редактирования пользователя</li>
 </ul>

</h5> 
