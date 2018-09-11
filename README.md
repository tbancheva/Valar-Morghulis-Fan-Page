# Valar-Morghulis-Fan-Page

Текущият проект представлява набор от няколко уеб страници, свързани с нашумелия сериал „Игра на тронове“.  

* **index.html** - Първата страница е своеобразен home page с логото на проекта и меню, водещо към другите страници. 
<p align="center">
  <img src="https://i.imgur.com/rMP0m3c.jpg" width=600 height=300/>
</p>

* **houses.html** - Страницата представлява описание на главните родове в сериала.
<p align="center">
  <img src="https://i.imgur.com/abDBqDo.jpg" width=600 />
</p>
При клик на някоя от иконите, потребителят се препраща към по подробно описание на конкретния род, както и вижда неговия банер.
<p align="center">
  <img src="https://i.imgur.com/uQ5d1Tf.jpg" width=600 />
</p>

* **religions.html** - Съдържа каросел със снимки свързани с основните религии в сериала, като при клик на всяка от тях, потребителят 
се препраща към по подробно описание на конкретната религия.
* **quiz.html** - Последната страница представлява динамичен куиз, чрез който всеки потребител може да провери дали има знанията на 
истински фен. Във всеки момент на екрана е показан по един въпрос, като при даване на отговор идва следващия въпрос, а след последния 
- потребителят вижда броя на верните отговори, които е дал. 

## Използвани технологии
* Всички страници са **responsive** , благодарение на използваните класове и темплейти от **Bootstrap** библиотеката. Също така имат и отделни
**css** файлове, отговарящи за стилизацията им.
* Информацията за родовете и религиите се зарежда чрез **AJAX** заявки към **json** обекти. В html страниците информацията се показва чрез
темплейти от **Handlebars** библиотеката. Използвана е и **jQuery** библиотеката.


