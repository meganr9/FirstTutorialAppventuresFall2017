# FirstTutorialAppventuresFall2017


1. Create Android Project
    a. Min SDK 15
    b. Create Empty Activity named MainActivity
2. Drag and drop a Button in the left pallete in the res/activity_main.xml
    (May need to go to Design tab on the bottom of the screen)
3. Go back to the xml view on the res/activity_main.xml file and go to the <button.. > element tag
     a. Type in
        android:onClick="pressedMeClicked" where pressedMeClicked is the name
        of the java function you wish to call when you click the button.
     b. Click the green part of the text, click the yellow lightbulb that shows up
        and hit the Create Event Handler option.
4. Go back to the res/activity_main.xml design view and click the textview that says
   "Hello World!" and change the id in the properties panel to mytextview
5. Edit the java/.../MainActivity.java file to look like the one in this project and
    hit the green play button!