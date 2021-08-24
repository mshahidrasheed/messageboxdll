# Custom Message Box, Custom Design
Custom message box is a windows form application. Displays a message window, also known as a dialog box, which presents a message to the client. 
A CustomMessageBox can contain three kinds of message boxes which show diffrent style of message dialogues

# Step 1:
* Clone this project and load into Visual Studio
* Build this project
* Or find already Build MyMessageBox.dll file in Build folder

# Step 2:
* Add MyMessageBox.dll file in your current project References
* Add namespace of MyMessageBox in your Class

**using MyMessageBox;**

* Call Show() function using Class name.

There are three types of message box available
* MessageBoxNotify
* MessageBoxOk
* MessageBoxYesNo

# MessageBoxNotify
MessageBoxNotify show notification message and then hide automatically.

# MessageBoxOk
MessageBoxOk show notification message and then wait for Ok click response.

# MessageBoxYesNo
MessageBoxYesNo show notification message and then wait for Yes / No click response.

# For Example

MessageBoxNotify.Show("message", "title", MessageBoxType.INFO);

MessageBoxOk.Show("message", "title", MessageBoxType.INFO);

MessageBoxYesNo.Show("message", "title", MessageBoxType.INFO);
