Keyboard TextField Manager
==========================
Often while developing an app, We ran into an issues where the iPhone UIKeyboard slide up and cover the UITextField/UITextView.

You can use IQKeyboardManager to fix this issue with just one line of code:-

[IQKeyBoardManager installKeyboardManager];


Just drag and drop IQKeyboardManager and IQSegmentedNextPrevious classes in your project. In your appDelegate write just one line of code. This will handle all UITextField/UITextView covering problem.


Feature:-
1) Support Device Orientation.
2) Easy integration.
3) UITextField Category for easily adding Next/Previous and Done button as Keyboard UIToolBar.