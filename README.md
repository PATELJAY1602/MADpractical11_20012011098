# MADpractical11_20012011098
Study: SQlite Database, RecyclerView, Broadcast Receiver, Service, Notification, Custom Alert Dialog Box, Time Picker Dialog, AlarmManager

AIM: Create Note Android Application that can add Note, edit Note, delete Note, and set reminder date & time of note. By using Broadcast Receiver, AlarmManager set reminder of note. By using SQLite, store all notes data.

Create two Activities like MainActivity, NoteViewActivity according to below UI design.

Use RecyclerView Code from Practical-9 to display Note Data.

Use Broadcast Receiver, Time Picker Dialog, service & AlarmManager code from Practical-7

Create Note class with member variables like id, title, subTitle, Description, modifiedTime, reminderTime:Long, isReminderEnable:Boolean & create membor methods like getCurrentDateTime(), getMillis(), setReminder(), isValid(), getReminderText(), saveNote(), getHour(), getMinute(), calculateReminder() 

Create DatabaseHelper Class for SQlite with member methods like insertNote(), getNote(id), getAllNotes(), getNotesCount(), updateNote(), deleteNote().

Use Databinding in gradle file to easy way integrate xml into kotlin file

Use Material 3 design for UI

create class NotesData with companion object and it will store column name of table and create table query.

Create NoteViewActivity. It will show while reminder notification is turned up and user click on notification. It will also show when click on Note in recyclerView. After clicking on notification NoteViewActivity should be open with full description of that note. 

Note should be deleted by clicking on icon of Delete. Note should not be added if any one field of note is empty.

Some notes have reminder time so add reminder time in alarmManager with note id & it should be receive in broadcast receiver & in broadcast receiver notification should be generated with title & description of note.

If More than one notes have reminder time then notification should be displayed for each note separately.

Create Common Custom Dialog Box for add, edit note.

Create RecyclerView & its adapter to display all notes.

Light Mode :

![image](https://user-images.githubusercontent.com/110656702/202912991-b508ef9d-8d79-4a9e-9c17-848a63a7acfe.png)

![image](https://user-images.githubusercontent.com/110656702/202913001-b393afd2-8e4e-440b-bcf4-203108c9c01d.png)

![image](https://user-images.githubusercontent.com/110656702/202913005-2b872e59-0787-4283-b1df-4b5a3cb5a6e0.png)

![image](https://user-images.githubusercontent.com/110656702/202913016-b659cc2e-591a-4f2c-a126-c141f2f5fd31.png)

![image](https://user-images.githubusercontent.com/110656702/202913026-da525971-412e-4d83-b97e-77c7b6505bf5.png)

Dark mode :

![image](https://user-images.githubusercontent.com/110656702/202913084-d29f63ac-76cc-4f8e-b0ad-8aeb5ba818b6.png)

![image](https://user-images.githubusercontent.com/110656702/202913100-7d4fccb0-84b1-4d59-81fa-5a6ad224085b.png)

![image](https://user-images.githubusercontent.com/110656702/202913091-917495b7-0ad1-4759-8a64-0297a1585ca5.png)

![image](https://user-images.githubusercontent.com/110656702/202913121-b28bf9ff-ab32-42c5-9013-9f653939bd4a.png)

![image](https://user-images.githubusercontent.com/110656702/202913127-ccfc0793-bca8-4b4d-8e4a-a1048bce87c7.png)


     
 
   
