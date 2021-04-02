# ToDoIT
Task is a concise to-do list app that can assist you in planning, monitoring, and completing further activities. You can create an infinite number of assignments, delegate them to team members, and create to-do lists within them. 

## Todo job features covers Add, Erase, Edit, and Read (CRUD) operations.
- To delete a task, use the swipe right to delete left functionality or click button.
- To update a task, use the swipe left to right functionality or click button.
- SQL Firebase Database login and registration functionality.
- User Validation email will be sent to their email address.
- Task details is stored in a SQLite folder.
- Database testing done.

Login          |  Register                      | Login with Email & Password              |  Notification Alert
:----------------------------:|:--------------------------------------:|:----------------------:|:-----------------
<img src="TodoImage/1st.png" width="200" height="360">  |  <img src = "TodoImage/2nd.png" width="200" height="360">        |  <img src = "TodoImage/3rd.png" width="200" height="360">  | <img src = "TodoImage/4th.png" width="200" height="360">
#
Dashboard          |  Added Task                   | After Added Task              |  Swipe Left to Delete The Task 
:----------------------------:|:--------------------------------------:|:----------------------:|:-----------------
 <img src = "TodoImage/5th.png" width="200" height="360"> |   <img src = "TodoImage/6th.png" width="200" height="360">        | <img src = "TodoImage/7th.png" width="200" height="360">   | <img src = "TodoImage/8th.png" width="200" height="360">
#
After Deteled The Task    |  Swipe Right to Update The Task       | After Update The Task     |  Logout
:----------------------------:|:--------------------------------------:|:----------------------:|:-----------------
 <img src = "TodoImage/9th.png" width="200" height="360"> |   <img src = "TodoImage/10th.png" width="200" height="360">        | <img src = "TodoImage/afterupdate.png" width="200" height="360">   | <img src = "TodoImage/11th.png" width="200" height="360">
#
Forget Paasword          |  Rotate the Task 
:----------------------------:|:--------------------------------------
 <img src = "TodoImage/12th.png" width="200" height="360"> |   <img src = "TodoImage/RotateInterface.PNG" width="360" height="200">
 


# Documentation

<b>Android Architecture Components</b> are a series of libraries that help you build more scalable, testable, and maintainable applications by allowing you more leverage over data persistence and lifecycle management. To access the program, users must first log in, and all data is displayed for all users. In the future, only the user will be able to display their data, and all entry users will not be able to see the data of other users.

# MVVM
Model–view–viewmodel (MVVM) is a software architectural pattern that allows the development of the graphical user interface (the view), whether using a markup language or GUI code, to be separated from the development of the business logic or back-end logic (the model), so that the view is independent of the model platform. The MVVM view model is a value converter, which means it's in charge of exposing (converting) data objects from the model in a way that makes them manageable and presentable. In this way, the view model is more model than view, since it is responsible for the bulk, if not all, of the view's display logic.The view model could use a mediator pattern to organize access to the back-end logic around the set of use cases that the view supports.
There are 3 parts to the Model-View-ViewModel architecture:-

   1. Your app's data layer is called a <b><u>Model</u></b>. The data source is abstracted.
   2. <b><u>View</u></b> contains the UI of your app. Most often it’s implemented as an Activity or Fragment. View informs ViewModel of user interactions and displays results received from the ViewModel. View should be lightweight and contain zero to very little business logic.
   3. <b><u>ViewModel</u></b> serves as a bridge between your View and Model. It works with the Model to get and save the data. The View observes and reacts to the data changes exposed by the ViewModel.

Here is a typical high-level MVVM app architecture:

<img src="TodoImage/MVVM.png" width="360" height="360">

## License
Copyright 2021 Pradip, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor license agreements. See the NOTICE file distributed with this work for additional information regarding copyright ownership. The ASF licenses this file to you under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
