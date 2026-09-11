# Mobile-Application-Development-
MAD( (Flutter)
Muhammad Ali Shah
04072313023

Task 6:
When you change a variable in your code,
flutter doesn't  notice, so the screen stays the exact same.
Putting your code inside setState(() {...}) tells flutter that something updated and it needs to recreate the page .
Without it, your variables might change in the background, but the app won't show any of those updates to the user.
