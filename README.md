# Firebase-ChatApp-RealtimeDatabase-master
Firebase chat applicatiom
1.	Creating the back-end for the app:
a.	Initially navigate to the Firebase Console web page
b.	Create a new project
c.	From the FriendlyChat project page in the Firebase Console, select “Add Firebase to your Android App”. 
This opens a dialog window that asks for your app’s Package name and the Debug signing certificate SHA-1.
2.	Add the dependencies to the android project
a.	compile 'com.google.firebase:firebase-database:10.2.1'
compile 'com.google.firebase:firebase-auth:10.2.1'
compile 'com.firebaseui:firebase-ui-auth:1.2.0'
compile 'com.google.firebase:firebase-storage:10.2.1'

3.	Create the Main Activity page and code it features as per requirement. friendly Chat utilizes particularly the chat room feature which has been coded into this project.
4.	Create a MessageAdapter class to handle the transfer of messages.
5.	Design the layout for the main activity of the app.
6.	Desing the layout for the item message page and the main menu page of the app
7.	Run the app via an AVD or via a connected android device. For testing a minimum of two devices shall be required.
 •	The App features a google+ sign in.
•	A user might have this app on his/her device, but to use this app the user has to be signed into his/her google account for verification.
•	The App is supported by a realtime update database (in the form of Firebase)
•	The messages sent by users to each other over the App are initially stored in the database, which in realtime, forwards it to other users.
•	The App data is stored on the device, allowing the user to view the data even when there is no internet connection.
•	The App features in the Chat-room functionality that allows users to create chat rooms to carry out conversations about a specific topic.
•	The following images show the Firebase console for the same:


MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
