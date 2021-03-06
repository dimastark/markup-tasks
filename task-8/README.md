# Задача «айБабулька»

__Задание необходимо решить без использования JS и с использованием CSS преобразований и переходов/анимаций__

Витрина лучших экземпляров осеннего урожая пользуется популярностью и одна грушевая компания обратила на нее внимание. Эта компания готова рекламировать продукцию бабуленек за скромные три ящика моркови.

Однако, для запуска рекламной кампании необходимо сверстать 3D галерею продуктов. Это обязательное условие грушевой компании и никакие овощные «подарки» не изменят их решение. Придется постараться.

<a href="https://cloud.githubusercontent.com/assets/4165695/11270678/bc99db5c-8ee2-11e5-95ea-368584ff3f83.png" target="_blank">
    <img width="300" src="https://cloud.githubusercontent.com/assets/4165695/11270678/bc99db5c-8ee2-11e5-95ea-368584ff3f83.png">
</a>

* На странице отображается 7 фотографий (макет №1)
* Фотография по центру (активная) отображается без искажения на переднем фоне
* Фотографии слева и справа от активной «повернуты» к ней и находятся «позади» нее
* Необходимо добиться ощущения 3D пространства
    * Активная фотография находиться в плоскости экрана
    * Неактивные фотографии «отодвинуты» от плоскости экрана «вглубь» на одинаковое расстояние 
    * Чем дальше фотография от активной - тем меньше ее поворот
* При клике на неактивную фотографию - она становится активной (макет №2)
    * Происходит анимированное перемещение фотографии в центр
    * При перемещении фотография постепеннно теряет искажение и в конечном итоге располагается в плоскости экрана в «стандартном» 2D виде
    * Остальные фотографии перемещаются вслед за новой активной
* При наведении на активную фотографию (и только на нее) у нас появляется ссылка на рецепт блюда из этого овоща (макет №3).
    * Анимацию появления ссылки на рецепт вы можете придумать сами.
    * При клике на эту ссылку карточка плавно разврачивается к нам «задней» стороной и увеличивается (создавая эффект «полета» к нам на встречу из экрана, макеты №4-6). Мы видим название блюда и рецепт (макет №7).
    * По клику на крестик анимация воспроизводится в обратном направлении, возвращая слайдер к состоянию до клика.

### Дополнительное задание (+56 к урожайности)

__Дополнительное задание необходимо решить без использования JS и с использованием CSS преобразований и переходов/анимаций__

Бабуленька не какой-то там ламер в области интернет маркетинга, а вполне даже продвинутый юзер и просит вас поиграть с перспективой и поворотом овощей. Или, если говорить языком макетов, то вам нужно реализовать переключение галереи (уже знакомым вам по прошлым заданиям способом) в другой 3d вид, с сохранением всех остальных функциональностей. Этот другой вид может быть таким:
![3d карусель](https://cloud.githubusercontent.com/assets/357689/20518241/9f1ecdc2-b0c8-11e6-84b6-7cf64b62e3c2.png)

А может быть вы придумаете ещё более красивый способ расположить овощи, фантазия здесь только приветствуется!

![Откормленные внуки](https://cloud.githubusercontent.com/assets/4165695/11269790/442a5dba-8edb-11e5-9c1a-194fe2e9bed9.jpeg)

:warning: При разработке 3D галереи ни один внук не остался голодным
