# Git

![image](https://user-images.githubusercontent.com/46717969/137625760-55f89aee-a5d6-43db-9443-d9024a3962af.png)

Git — розподілена система керування версіями файлів та спільної роботи. Проєкт створив Лінус Торвальдс для керування розробкою ядра Linux, а сьогодні підтримується Джуніо Хамано (англ. Junio C. Hamano). Git є однією з найефективніших, надійних і високопродуктивних систем керування версіями, що надає гнучкі засоби нелінійної розробки, що базуються на відгалуженні і злитті гілок. Для забезпечення цілісності історії та стійкості до змін заднім числом використовуються криптографічні методи, також можлива прив'язка цифрових підписів розробників до тегів і комітів.

Прикладами проєктів, що використовують Git, є ядро Linux, Android, LibreOffice, Cairo, GNU Core Utilities, Mesa 3D, Wine, багато проєктів з X.org, XMMS2[en], GStreamer, Debian DragonFly BSD, Perl, Eclipse, GNOME, KDE, Qt, Ruby on Rails, PostgreSQL, VideoLAN, PHP, One Laptop Per Child (OLPC), АБІС Koha, GNU LilyPond та ELinks і деякі дистрибутиви GNU/Linux (див. нижче).

> Програма є вільною і випущена під ліцензією **GNU GPL** версії 2.

Система спроєктована як набір програм, спеціально розроблених з врахуванням їхнього використання у скриптах. Це дозволяє зручно створювати спеціалізовані системи керування версіями на базі Git або користувацькі інтерфейси. Наприклад, Cogito[en] є саме таким прикладом фронтенда до репозиторіїв Git. А StGit використовує Git для управління колекцією латок. 

Віддалений доступ до репозиторіїв Git забезпечується git-демоном, SSH або HTTP сервером. TCP-сервіс git-daemon входить у дистрибутив Git і є разом з SSH найпоширенішим і надійним методом доступу. 

> Метод доступу **HTTP**, незважаючи на ряд обмежень, дуже популярний в контрольованих мережах, тому що дозволяє використання існуючих конфігурацій мережевих фільтрів.

# Консольні команди для створення нового репозиторію

```
echo "# LR_1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/alina-tushych/LR_1.git
git push -u origin master
```
# Консольні команди для підключення до існуючого репозиторію

```
git remote add origin https://github.com/alina-tushych/LR_1.git
git branch -M master
git push -u origin master
```
# Інші базові команди

![image](https://user-images.githubusercontent.com/46717969/137625839-d185333a-9361-432d-849b-d91d92aefcf6.png)

# Посилання

[Wikipedia][1]

[Документація][2]

[Підручник][3]

[Завантажити програмне забезпечення][4]

[Створення простого репозиторію (відео Аліна Тушич)][5]


[1]: https://uk.wikipedia.org/wiki/Git
[2]: https://git-scm.com/docs
[3]: https://git-scm.com/book/uk/v2
[4]: https://git-scm.com/downloads
[5]: https://youtu.be/RVOq9PnociQ
