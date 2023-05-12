# TodoApp

<h1>Features of TodoApp</h1>
<ul>
	<li>Create a new todo with a title, description, completion status, and date.</li>
	<li>Edit the todo that were added by double tab the given each lists.</li>
	<li>Display the todo specific to the user in the home page.</li>
	<li>Delete individual todo by swiping.</li>
	<li>Delete all the todos that are completed.</li>
	<li>Delete all the todos.</li>

</ul>

<h1>Additional features</h1>
<ul>
    <li>Perform validation for the todo form.</li>
	<li>Update the completion status of a todo directly from the home page.</li>
	<li>Enable multiple account registration and login.</li>
	<li>View your profile information and modify your password.</li>
	<li>Permanently remove your account.</li>

</ul>


### Registration


**Registration is necessary to access the login feature.**

![signup](gif/signup.gif)

**The registration process requires unique and non-empty information for each field.**


![signupValidation](gif/validation.gif)

**The above two records showcase the registration form with validations for empty fields, existing user, and password mismatch. Once the registration process is successfully completed, a toast message will be displayed, indicating that the registration was successful.**

---

### Login

**Login validation has been implemented. Once the user has successfully logged in, they will be directed to the main page.**

![login](gif/login.gif)

**The following record pertains to the login system in the application, which includes validation for non-existent users, empty fields, and mismatched username and password. Upon successful login, the user will be redirected to the todo list page, which allows them to view their profile, delete completed tasks only, delete all tasks, log out of their account, and perform CRUD operations on their tasks.**

---

### Add

**The process of adding items to the list has been implemented..**

![Add](gif/add.gif)

**The following record demonstrates the process of adding tasks to the todo list. To add a task, the user can click on the floating action button located in the bottom left corner of the screen. This action will direct the user to the task insertion form, where they can enter the task details. The form also includes some validation checks. Upon clicking the save button, the user will be redirected to the todo list page, where the task details will be displayed based on the chosen priority color for each task.**

---

### Update

**To update a given item in the list, the user can double-tap on the item. This action will open the item for editing, and the user can modify the details as needed before saving the changes.**

![update](gif/update.gif)

**This record outlines the update process for a task, which involves using a double-tap event on the task to initiate the update. Once the double-tap event is triggered, the user will be directed to the task update form, which will contain the relevant information for that task. After making the necessary updates, the user can save the changes by clicking the update button. Upon completion, the user will be redirected back to the todo list page. If the user clicks the cancel button, the changes will not be saved for that task.**

---

### Delete

**To delete a task, the user can swipe left or right on the task. This action will prompt a delete confirmation message to ensure that the user wants to delete the task. If confirmed, the task will be removed from the list.**

![Delete](gif/delete.gif)

**When a user swipes a task left or right, the task will be automatically deleted. A confirmation message will appear to ensure that the user wants to delete the task. After confirmation, the task will be removed from the list and a toast message will appear to confirm that the task has been deleted.**

---


### User Profile

**On the user profile page, users can update their password and delete their account password. This functionality allows users to keep their account secure and make changes as needed.**

![profile](gif/profile.gif)

**By clicking the profile name or icon from the toolbar, users will be redirected to their user profile page. From this page, they can delete their personal account and update their password to maintain account security. This feature ensures that users have control over their accounts and can make necessary changes as needed.**

---

### List

**Users can view their list of data on the application's main page, where all their tasks are displayed.**

![scroll-list](gif/scroll.gif)

**This page displays all the todo tasks that the user has added to their list.**

---

### On the todo list page, users have the option to delete all tasks that are marked as completed. 

**To delete completed tasks only from the todo list, the user can open the menu options and select the "Delete Completed" option.**

![deleteCompletedTask](gif/deleteCompleted.gif)

---

### Delete All

**The user can open the menu options and select the "Delete All" option.**

![deleteAll](gif/deleteAll.gif)

---

### Delete Profie

**The user can open the profile and select the "Delete Profile" option.**

![deleteProfile](gif/deleteProfile.gif)

---

### Logout

**The user can click on the power off button located on the menu bar.**

![logout](gif/logout.gif)

---

### Landscape 

**running the entire application in landscape mode.**

![rotate](gif/rotate.gif)

**The above record displays the application's page in landscape orientation.**

---

