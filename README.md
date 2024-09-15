Описание:<br />
• Приложение "Постер", представляющий список карточек, содержащих заголовок, текст и кнопки "Прочитано", "Не прочитано".<br />
• Пагинация реализована на основе смещения — иногда называемая пагинацией набора ключей или пагинацией на основе поиска.<br />
  "Бесконечная прокрутка" реализована с помощью пакета "react-infinite-scroll-component".<br />
• В проекте "Poster.Tests" реализовано тестирование backend части.<br />
• Хранение постов вынесено в глобальное хранилище состояний с помощью Redux.<br />
• В файле "appsettings.json", секции "Cors" проекта Poster.WebApi необходимо указать адрес сервера на котором располагается "Фронтенд" часть для выполнения
  кросс-доменные запросы.<br />
• В файле ".env" проекта Poster.UI для переменной "VITE_POSTS_SERVER" необходима указать адрес сервера "Poster.WebApi" для выполнения запросов на управление постами.<br />
<br />
Frontend:<br />
• React<br />
• Axios<br />
• Redux<br />
<br />
Backend:<br />
• .NET 8<br />
• Swagger<br />
• EntityFramework<br />
• Clean arhitecture<br />
• Testing - XUnit, Moq<br />
