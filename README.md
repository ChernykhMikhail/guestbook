# Guestbook

Liferay Guestbook Web Application created from scratch using tools like **IntelliJ IDEA IDE** and **BLADE CLI**.

In order to initialize a new project navigate to a folder where you want to place your Lifray project and use follow command:

`blade init guestbook`

To create a new portlet run follow command:

`blade create -t mvc-portlet -p com.liferay.docs.guestbook.portlet -c Guestbook guestbook-web` 

To create a service builder use follow command:

`blade -t service-bulder -p com.liferay.docs.guestbook guestbook`

To start the server run follow command:

`blade server start`

To deploy the project run follow command:

`blade deploy`