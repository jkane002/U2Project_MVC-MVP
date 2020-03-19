# U2Project_MVC-MVP
Unit 2 Project MVC/MVP

**Project Name:** Login Screen

**Project Description:** For this project, we expand more on MVC and implement an application of it - the MVP design pattern. Remember that MVC stands for Model, View, and Controller. Now MVP stands for Model, View, and Presenter. We discuss the differences in the background section below. This simple login screen application explicitly highlights the MVP pattern. This can also be used in future applications and projects enhancing user experience and mimicking daily applications on the App store.

![File diagram](https://drive.google.com/uc?id=128QWeQwKqzK4U7uvC6M2GbB13UkdyzEv)


**Differences between MVC and MVP:**

Model View Controller
* Controllers are behavior based and can share multiple views.
* View can communicate directly with Model

Model View Presenter
* In MVP, the role of the controller is replaced with a Presenter.
* Presenters sit at the same level as views, listening to events from both the View and model, and mediating the actions between them.
* View more separated from Model. The Presenter is the mediator between Model and View.
* Generally there is a one to one mapping between View and Presenter, with the possibility to use multiple Presenters for complex Views
* Listen to user action and model updates
* Updates model and view as well
