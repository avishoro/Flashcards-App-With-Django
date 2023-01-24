# Flashcards-App-With-Django
In this project, we build a [flashcards](https://en.wikipedia.org/wiki/Flashcard) app, and the database based on Leitner system, a method who based on spaced repetition, where cards are reviewed at increasing intervals (for more information about Leitner system, see [here](https://en.wikipedia.org/wiki/Leitner_system).

![image](https://user-images.githubusercontent.com/93486933/214278773-54cfddfa-ec57-46a0-861e-ca20a4877984.png)


In our example, we used the app to practice capital cities, but you can use the app to any type of practice you want.
* We have five boxes that can contain flashcards.
* When you create a flashcard, you put it into the first box.
* To test your knowledge, you choose a box, pick a random flashcard, and check if you know the answer to the card’s question.
* If you know the answer, then you move the card to the next higher box.
* If you don’t know the answer, then you move the card back to the first box.

**Follow the next steps to create the app:**

* Clone the folders from [Flashcards_app](https://github.com/avishoro/Flashcards-App-With-Django/tree/main/Flashcards_app).
* Create virtual enviorment:\
    PS> python -m venv venv\
    PS> .\venv\Scripts\activate\
    (venv) PS>
* Install [django](https://en.wikipedia.org/wiki/Django_(web_framework)) with [pip](https://en.wikipedia.org/wiki/Pip_(package_manager)).\
    (venv) $ python -m pip install django==4.0.4   
* Run your development web server:\
    (venv) $ python manage.py runserver
* Now, you can go to your Django project in your browser by using http://127.0.0.1:8000 

You can add new item by clicking on "Create New Card" button.
![image](https://user-images.githubusercontent.com/93486933/214270346-7ed26209-d135-4e1c-8b81-8892e73928c3.png)

Add the question and the answer, and click "save card" or the cancel button.\
By default, new card go to the first box, but you can chang that if you want.\
![image](https://user-images.githubusercontent.com/93486933/214270878-29d8542d-59c7-4e0e-a72c-32f1af3eb9a9.png)
For practice, go to the first box and check if you remember the answer, you can click on "Reval Answer" to see the answer and check if you correct\
if you click "I know", the card will move to the next box, if uou click "I don't know" the card will go back to the first box.\
![image](https://user-images.githubusercontent.com/93486933/214277679-d4d0288c-d29b-46a6-9895-e79c45f9bfa7.png)





