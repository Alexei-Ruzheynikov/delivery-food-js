# delivery-food-js

Разработал:
Кнопки авторизации.Недопустимость пустого логина при входе.
При открытии модального окна, отключается скролл. Устранен баг езды верстки при открытии модального окна из-за скролла. Скролл запоминается и возвращается на то же место при открытии и закрытии модального окна

Пометки: объект evenet, у него есть свойство target
const target = event.target;
const restaurant = target.closest(".card-restaurant");
closest - всплытие событий, при клике на дочерний элемент, closest - всплывает до нужного класса .card-restaurant и засчитывая клик возвращает true

Добавлять HTML лучше с помощью insertAdjacentHTML

Простой плагин слайдера на js https://pawelgrzybek.github.io/siema/
