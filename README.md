Project from a test-task.

Тестовое задание:

Концепция

Данная система позволяет нескольким пользователям сохранять мнения и оценки нескольких 

продуктах. Пользователи имеют возможность просматривать оценки и мнения других пользователей.

Первая страница

На первой странице пользователь должен ввести имя пользователя и пароль. Все остальные 

страницы доступны только после правильного ввода имени пользователя и пароля.

Вторая страница

На второй странице пользователь видит список продуктов. В этом списке для каждого продукта 

показываются: название продукта, меню для выбора рейтинга (от 1 до 5), поле для ввода 

комментария. Когда пользователь заходит на эту страницу, в меня для выбора рейтинга должен 

показаться рейтинг, который пользователь поставил продукту в последний раз, а в поле комментария 

– комментарий, который пользователь написал в последний раз. В списке пользователь может 

изменить рейтинг и комментарий, после чего нажать кнопку “Сохранить”. После этого введенная 

информация сохранится в базе данных, а пользователь снова окажется на странице со списком 

продуктов. Пользователь может несколько раз поставить рейтинг одному и тому же продукту, при 

этом система будет использовать рейтинг, который был поставлен в последний раз. Если 

пользователь поставил рейтинг продукту, то он может его и убрать.

Третья страница

Название продукта на второй странице является ссылкой на третью страницу. На третьей странице 

написано название продукта, ниже идет список пользователей. Для каждого пользователя в этом 

списке пишется следующая информация: имя пользователя (то же самое имя, которое используется 

при входе в систему), рейтинг, который данный пользователь поставил данному продукту, 

комментарий данного пользователя о данном продукте. Если пользователь не поставил рейтинг 

продукту, то он не пишется в данном списке. Внизу списка пишется сумма всех рейтингов и среднее 

значение рейтинга для данного продукта.
