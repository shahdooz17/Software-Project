# Functional Requirments
--------------------------------
**In Functional requirments we have two modules: 1-Admin module 2-User Module.**


## Admin Module

### Authentication

| User Requirement                                                         |
| ------------------------------------------------------------------------ |
| The system shall allow the admin to login using a username and password. |

| System Requirement                                                                                                |
| ----------------------------------------------------------------------------------------------------------------- |
| 1. The system will check the username against the database.                                                       |
| 2. If the username is found, the system will check the password against the database else system will show error. |
| 3. If the password is correct, the system will allow the admin to login else system will show error.              |
| Pre-conditions:                                                                                                   |
| - Admin must type his informations.                                                                               |
| Post-conditions:                                                                                                  |
| - Admin will enter his profile if his information founded and valid.                                              |
| - Admin will see an error message if his information not founded or invalid.                                      |

### Logout

| User Requirement                                            |
| ----------------------------------------------------------- |
| The system shall allow the admin to logout from the system. |

| System Requirement                                           |
| ------------------------------------------------------------ |
| 1. The system will clear the admin's session.                |
| 2. The system will redirect the admin to the login page.     |
| Pre-conditions:                                              |
| - Admin must be logged in.                                   |
| Post-conditions:                                             |
| - Admin will be logged out and redirected to the login page. |

### View Users

| User Requirement                                                  |
| ----------------------------------------------------------------- |
| The system shall allow the admin to view all users in the system. |

| System Requirement                                                                   |
| ------------------------------------------------------------------------------------ |
| 1. The system will retrieve all users from the database.                             |
| 2. The system will display the users' usernames, emails, reputation points and role. |
| Pre-conditions:                                                                      |
| - Admin must be logged in.                                                           |
| Post-conditions:                                                                     |
| - The system will display all users in the system.                                   |

### Add New User

| User Requirement                                                  |
| ----------------------------------------------------------------- |
| The system shall allow the admin to add a new user to the system. |

| System Requirement                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------- |
| 1. The system will allow the admin to enter the user's username, email, password and checkbox to make user admin or no. |
| 2. The system will check the username and email against the database.                                                   |
| 3. If the username and email are not found, the system will add the user to the database.                               |
| 4. If the username or email is found, the system will show an error message.                                            |
| Pre-conditions:                                                                                                         |
| - Admin must type the user's informations.                                                                              |
| Post-conditions:                                                                                                        |
| - The user will be added to the database if his information is valid.                                                   |
| - The system will show an error message if the user's information is not valid.                                         |

### Delete User

| User Requirement                                                   |
| ------------------------------------------------------------------ |
| The system shall allow the admin to delete a user from the system. |

| System Requirement                                                              |
| ------------------------------------------------------------------------------- |
| 1. The system will allow the admin to enter the user's username.                |
| 2. The system will check the username against the database.                     |
| 3. If the username is found, the system will delete the user from the database. |
| 4. If the username is not found, the system will show an error message.         |
| Pre-conditions:                                                                 |
| - Admin must type the user's username.                                          |
| Post-conditions:                                                                |
| - The user will be deleted from the database if his information is valid.       |
| - The system will show an error message if the user's information is not valid. |

### Update User

| User Requirement                                                 |
| ---------------------------------------------------------------- |
| The system shall allow the admin to update a user's information. |

| System Requirement                                                                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------------------ |
| 1. The system will allow the admin to enter the user's username, email, password, reputation points and checkbox to make user admin or no. |
| 2. The system will check the username and email against the database.                                                                      |
| 3. If the username and email are found, the system will update the user's information in the database.                                     |
| 4. If the username or email is not found, the system will show an error message.                                                           |
| Pre-conditions:                                                                                                                            |
| - Admin must type the user's informations.                                                                                                 |
| Post-conditions:                                                                                                                           |
| - The user's information will be updated in the database if his information is valid.                                                      |
| - The system will show an error message if the user's information is not valid.                                                            |

### View Questions

| User Requirement                                                      |
| --------------------------------------------------------------------- |
| The system shall allow the admin to view all questions in the system. |

| System Requirement                                                                   |
| ------------------------------------------------------------------------------------ |
| 1. The system will retrieve all questions from the database.                         |
| 2. The system will display the questions' titles, descriptions, tags and reputation. |
| Pre-conditions:                                                                      |
| - Admin must be logged in.                                                           |
| Post-conditions:                                                                     |
| - The system will display all questions in the system.                               |

### Add New Question

| User Requirement                                                      |
| --------------------------------------------------------------------- |
| The system shall allow the admin to add a new question to the system. |

| System Requirement                                                                      |
| --------------------------------------------------------------------------------------- |
| 1. The system will allow the admin to enter the question's title, description and tags. |
| 2. The system will check the title against the database.                                |
| 3. If the title is not found, the system will add the question to the database.         |
| 4. If the title is found, the system will show an error message.                        |
| Pre-conditions:                                                                         |
| - Admin must type the question's informations.                                          |
| Post-conditions:                                                                        |
| - The question will be added to the database if his information is valid.               |
| - The system will show an error message if the question's information is not valid.     |

### Delete Question

| User Requirement                                                       |
| ---------------------------------------------------------------------- |
| The system shall allow the admin to delete a question from the system. |

| System Requirement                                                                  |
| ----------------------------------------------------------------------------------- |
| 1. The system will allow the admin to enter the question's title.                   |
| 2. The system will check the title against the database.                            |
| 3. If the title is found, the system will delete the question from the database.    |
| 4. If the title is not found, the system will show an error message.                |
| Pre-conditions:                                                                     |
| - Admin must type the question's title.                                             |
| Post-conditions:                                                                    |
| - The question will be deleted from the database if his information is valid.       |
| - The system will show an error message if the question's information is not valid. |

### Update Question

| User Requirement                                                     |
| -------------------------------------------------------------------- |
| The system shall allow the admin to update a question's information. |

| System Requirement                                                                           |
| -------------------------------------------------------------------------------------------- |
| 1. The system will allow the admin to enter the question's title, description and tags.      |
| 2. The system will check the title against the database.                                     |
| 3. If the title is found, the system will update the question's information in the database. |
| 4. If the title is not found, the system will show an error message.                         |
| Pre-conditions:                                                                              |
| - Admin must type the question's informations.                                               |
| Post-conditions:                                                                             |
| - The question's information will be updated in the database if his information is valid.    |
| - The system will show an error message if the question's information is not valid.          |

### View Question

| User Requirement                                                   |
| ------------------------------------------------------------------ |
| The system shall allow the admin to view a question in the system. |

| System Requirement                                                                 |
| ---------------------------------------------------------------------------------- |
| 1. The system will retrieve the question's information from the database.          |
| 2. The system will display the question's title, description, tags and reputation. |
| Pre-conditions:                                                                    |
| - Admin must be logged in.                                                         |
| Post-conditions:                                                                   |
| - The system will display the question's information.                              |

### View Answers

| User Requirement                                                    |
| ------------------------------------------------------------------- |
| The system shall allow the admin to view all answers in the system. |

| System Requirement                                                                   |
| ------------------------------------------------------------------------------------ |
| 1. The system will retrieve all answers from the database.                           |
| 2. The system will display the answers' descriptions, reputation and question title. |
| Pre-conditions:                                                                      |
| - Admin must be logged in.                                                           |
| Post-conditions:                                                                     |
| - The system will display all answers in the system.                                 |

### Delete Answer

| User Requirement                                                      |
| --------------------------------------------------------------------- |
| The system shall allow the admin to delete an answer from the system. |

| System Requirement                                                                     |
| -------------------------------------------------------------------------------------- |
| 1. The system will allow the admin to delete the answer by pressing the delete button. |
| 2. The system will check the answer against the database.                              |
| 3. If the answer is found, the system will delete the answer from the database.        |
| 4. If the answer is not found, the system will show an error message.                  |
| Pre-conditions:                                                                        |
| - Admin must press the delete button.                                                  |
| Post-conditions:                                                                       |
| - The answer will be deleted from the database if his information is valid.            |
| - The system will show an error message if the answer's information is not valid.      |


### View Tags

| User Requirement                                                 |
| ---------------------------------------------------------------- |
| The system shall allow the admin to view all tags in the system. |

| System Requirement                                         |
| ---------------------------------------------------------- |
| 1. The system will retrieve all tags from the database.    |
| 2. The system will display the tags' names and reputation. |
| Pre-conditions:                                            |
| - Admin must be logged in.                                 |
| Post-conditions:                                           |
| - The system will display all tags in the system.          |

### Add New Tag

| User Requirement                                                 |
| ---------------------------------------------------------------- |
| The system shall allow the admin to add a new tag to the system. |

| System Requirement                                                             |
| ------------------------------------------------------------------------------ |
| 1. The system will allow the admin to enter the tag's name.                    |
| 2. The system will check the tag against the database.                         |
| 3. If the tag is not found, the system will add the tag to the database.       |
| 4. If the tag is found, the system will show an error message.                 |
| Pre-conditions:                                                                |
| - Admin must type the tag's informations.                                      |
| Post-conditions:                                                               |
| - The tag will be added to the database if his information is valid.           |
| - The system will show an error message if the tag's information is not valid. |

### Delete Tag

| User Requirement                                                  |
| ----------------------------------------------------------------- |
| The system shall allow the admin to delete a tag from the system. |

| System Requirement                                                        |
| ------------------------------------------------------------------------- |
| 1. The system will allow the admin to enter the tag's name.               |
| 2. The system will check the tag against the database.                    |
| 3. If the tag is found, the system will delete the tag from the database. |
| 4. If the tag is not found, the system will show an error message.        |
| Pre-conditions:                                                           |
| - Admin must type the tag's name.                                         |
| Post-conditions:                                                          |
| - The tag will be deleted from the database if his information is valid.  |

### Update Tag

| User Requirement                                                |
| --------------------------------------------------------------- |
| The system shall allow the admin to update a tag's information. |

| System Requirement                                                                    |
| ------------------------------------------------------------------------------------- |
| 1. The system will allow the admin to enter the tag's name and reputation.            |
| 2. The system will check the tag against the database.                                |
| 3. If the tag is found, the system will update the tag's information in the database. |
| 4. If the tag is not found, the system will show an error message.                    |
| Pre-conditions:                                                                       |
| - Admin must type the tag's informations.                                             |
| Post-conditions:                                                                      |
| - The tag's information will be updated in the database if his information is valid.  |
| - The system will show an error message if the tag's information is not valid.        |


### View Analytics

| User Requirement                                                      |
| --------------------------------------------------------------------- |
| The system shall allow the admin to view all Analytics in the system. |

| System Requirement                                            |
| ------------------------------------------------------------- |
| 1. The system will retrieve all Analytics from the database.  |
| 2. The system will display the Analytics' titles and reasons. |
| Pre-conditions:                                               |
| - Admin must be logged in.                                    |
| Post-conditions:                                              |
| - The system will display all Analytics in the system.        |

## User Module

### Authentication

| User Requirement                                                        |
| ----------------------------------------------------------------------- |
| The system shall allow the user to login using a username and password. |

| System Requirement                                                                                                |
| ----------------------------------------------------------------------------------------------------------------- |
| 1. The system will check the username against the database.                                                       |
| 2. If the username is found, the system will check the password against the database else system will show error. |
| 3. If the password is correct, the system will allow the user to login else system will show error.               |
| Pre-conditions:                                                                                                   |
| - User must type his informations.                                                                                |
| Post-conditions:                                                                                                  |
| - User will enter his profile if his information founded and valid.                                               |
| - User will see an error message if his information not founded or invalid.                                       |

### Register

| User Requirement                                                                  |
| --------------------------------------------------------------------------------- |
| The system shall allow the user to register using a username, email and password. |

| System Requirement                                                                        |
| ----------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the user's username, email and password.       |
| 2. The system will check the username and email against the database.                     |
| 3. If the username and email are not found, the system will add the user to the database. |
| 4. If the username or email is found, the system will show an error message.              |
| Pre-conditions:                                                                           |
| - User must type the user's informations.                                                 |
| Post-conditions:                                                                          |
| - The user will be added to the database if his information is valid.                     |
| - The system will show an error message if the user's information is not valid.           |

### Logout

| User Requirement                                           |
| ---------------------------------------------------------- |
| The system shall allow the user to logout from the system. |

| System Requirement                                          |
| ----------------------------------------------------------- |
| 1. The system will clear the user's session.                |
| 2. The system will redirect the user to the login page.     |
| Pre-conditions:                                             |
| - User must be logged in.                                   |
| Post-conditions:                                            |
| - User will be logged out and redirected to the login page. |

### View Profile

| User Requirement                                                 |
| ---------------------------------------------------------------- |
| The system shall allow the user to view his profile information. |

| System Requirement                                                                   |
| ------------------------------------------------------------------------------------ |
| 1. The system will retrieve the user's information from the database.                |
| 2. The system will display the user's username, email, reputation points and badges. |
| Pre-conditions:                                                                      |
| - User must be logged in.                                                            |
| Post-conditions:                                                                     |
| - The system will display the user's profile information.                            |

### Update Profile

| User Requirement                                                   |
| ------------------------------------------------------------------ |
| The system shall allow the user to update his profile information. |

| System Requirement                                                                                     |
| ------------------------------------------------------------------------------------------------------ |
| 1. The system will allow the user to enter the user's username, email and password.                    |
| 2. The system will check the username and email against the database.                                  |
| 3. If the username and email are found, the system will update the user's information in the database. |
| 4. If the username or email is not found, the system will show an error message.                       |
| Pre-conditions:                                                                                        |
| - User must type the user's informations.                                                              |
| Post-conditions:                                                                                       |
| - The user's information will be updated in the database if his information is valid.                  |
| - The system will show an error message if the user's information is not valid.                        |

### Delete Profile

| User Requirement                                                   |
| ------------------------------------------------------------------ |
| The system shall allow the user to delete his profile information. |

| System Requirement                                                              |
| ------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the user's username.                 |
| 2. The system will check the username against the database.                     |
| 3. If the username is found, the system will delete the user from the database. |
| 4. If the username is not found, the system will show an error message.         |
| Pre-conditions:                                                                 |
| - User must type the user's username.                                           |
| Post-conditions:                                                                |
| - The user will be deleted from the database if his information is valid.       |
| - The system will show an error message if the user's information is not valid. |

## Question Module

### View Questions

| User Requirement                                                     |
| -------------------------------------------------------------------- |
| The system shall allow the user to view all questions in the system. |

| System Requirement                                                                   |
| ------------------------------------------------------------------------------------ |
| 1. The system will retrieve all questions from the database.                         |
| 2. The system will display the questions' titles, descriptions, tags and reputation. |
| Pre-conditions:                                                                      |
| - User must be logged in.                                                            |
| Post-conditions:                                                                     |
| - The system will display all questions in the system.                               |

### Add New Question

| User Requirement                                                     |
| -------------------------------------------------------------------- |
| The system shall allow the user to add a new question to the system. |

| System Requirement                                                                     |
| -------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the question's title, description and tags. |
| 2. The system will check the title against the database.                               |
| 3. If the title is not found, the system will add the question to the database.        |
| 4. If the title is found, the system will show an error message.                       |
| Pre-conditions:                                                                        |
| - User must type the question's informations.                                          |
| Post-conditions:                                                                       |
| - The question will be added to the database if his information is valid.              |
| - The system will show an error message if the question's information is not valid.    |

### Delete Question

| User Requirement                                                        |
| ----------------------------------------------------------------------- |
| The system shall allow the user to delete his question from the system. |

| System Requirement                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the question's title.                                                        |
| 2. The system will check the title against the database.                                                                |
| 3. If the title is found and the question is belong to the user, the system will delete the question from the database. |
| 4. If the title is not found or the question is not belong to the user, the system will show an error message.          |
| Pre-conditions:                                                                                                         |
| - User must type the question's title.                                                                                  |
| Post-conditions:                                                                                                        |
| - The question will be deleted from the database if his information is valid.                                           |
| - The system will show an error message if the question's information is not valid.                                     |

### Update Question

| User Requirement                                                      |
| --------------------------------------------------------------------- |
| The system shall allow the user to update his question's information. |

| System Requirement                                                                                                                  |
| ----------------------------------------------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the question's title, description and tags.                                              |
| 2. The system will check the title against the database.                                                                            |
| 3. If the title is found and the question is belong to the user, the system will update the question's information in the database. |
| 4. If the title is not found or the question is not belong to the user, the system will show an error message.                      |
| Pre-conditions:                                                                                                                     |
| - User must type the question's informations.                                                                                       |
| Post-conditions:                                                                                                                    |
| - The question's information will be updated in the database if his information is valid.                                           |
| - The system will show an error message if the question's information is not valid.                                                 |

### View Question

| User Requirement                                                  |
| ----------------------------------------------------------------- |
| The system shall allow the user to view a question in the system. |

| System Requirement                                                                 |
| ---------------------------------------------------------------------------------- |
| 1. The system will retrieve the question's information from the database.          |
| 2. The system will display the question's title, description, tags and reputation. |
| Pre-conditions:                                                                    |
| - User must be logged in.                                                          |
| Post-conditions:                                                                   |
| - The system will display the question's information.                              |

### View Answers

| User Requirement                                                   |
| ------------------------------------------------------------------ |
| The system shall allow the user to view all answers in the system. |

| System Requirement                                                                   |
| ------------------------------------------------------------------------------------ |
| 1. The system will retrieve all answers from the database.                           |
| 2. The system will display the answers' descriptions, reputation and question title. |
| Pre-conditions:                                                                      |
| - User must be logged in.                                                            |
| Post-conditions:                                                                     |
| - The system will display all answers in the system.                                 |

### Add New Answer

| User Requirement                                                   |
| ------------------------------------------------------------------ |
| The system shall allow the user to add a new answer to the system. |

| System Requirement                                                                            |
| --------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the answer's description.                          |
| 2. The system will check the answer against the database.                                     |
| 3. If there is no answer belongs to the user in the question, the system will add the answer. |
| 4. If the answer is found, the system will show an error message.                             |
| Pre-conditions:                                                                               |
| - User must type the answer's informations.                                                   |
| Post-conditions:                                                                              |
| - The answer will be added to the database if his information is valid.                       |
| - The system will show an error message if the answer's information is not valid.             |

### Delete Answer

| User Requirement                                                      |
| --------------------------------------------------------------------- |
| The system shall allow the user to delete his answer from the system. |

| System Requirement                                                                                                   |
| -------------------------------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to delete the answer by pressing the delete button.                                |
| 2. The system will check the answer against the database.                                                            |
| 3. If the answer is found and the answer is belong to the user, the system will delete the answer from the database. |
| 4. If the answer is not found or the answer is not belong to the user, the system will show an error message.        |
| Pre-conditions:                                                                                                      |
| - User must press the delete button.                                                                                 |
| Post-conditions:                                                                                                     |
| - The answer will be deleted from the database if his information is valid.                                          |
| - The system will show an error message if the answer's information is not valid.                                    |

### Update Answer

| User Requirement                                                    |
| ------------------------------------------------------------------- |
| The system shall allow the user to update his answer's information. |

| System Requirement                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the answer's description.                                                             |
| 2. The system will check the answer against the database.                                                                        |
| 3. If the answer is found and the answer is belong to the user, the system will update the answer's information in the database. |
| 4. If the answer is not found or the answer is not belong to the user, the system will show an error message.                    |
| Pre-conditions:                                                                                                                  |
| - User must type the answer's informations.                                                                                      |
| Post-conditions:                                                                                                                 |
| - The answer's information will be updated in the database if his information is valid.                                          |
| - The system will show an error message if the answer's information is not valid.                                                |

### Upvote Answer

| User Requirement                                                   |
| ------------------------------------------------------------------ |
| The system shall allow the user to upvote an answer in the system. |

| System Requirement                                                                        |
| ----------------------------------------------------------------------------------------- |
| 1. The system will allow the user to upvote the answer by pressing the upvote button.     |
| 2. The system will check the answer against the database.                                 |
| 3. If the answer is found, the system will add 10 reputation points to the answer's user. |
| 4. If the answer is not found, the system will show an error message.                     |
| Pre-conditions:                                                                           |
| - User must press the upvote button.                                                      |
| Post-conditions:                                                                          |
| - The answer's user will get 10 reputation points if the answer is valid.                 |
| - The system will show an error message if the answer is not valid.                       |

### Downvote Answer

| User Requirement                                                     |
| -------------------------------------------------------------------- |
| The system shall allow the user to downvote an answer in the system. |

| System Requirement                                                                            |
| --------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to downvote the answer by pressing the downvote button.     |
| 2. The system will check the answer against the database.                                     |
| 3. If the answer is found, the system will remove 2 reputation points from the answer's user. |
| 4. If the answer is not found, the system will show an error message.                         |
| Pre-conditions:                                                                               |
| - User must press the downvote button.                                                        |
| Post-conditions:                                                                              |
| - The answer's user will lose 2 reputation points if the answer is valid.                     |
| - The system will show an error message if the answer is not valid.                           |

### Upvote Question

| User Requirement                                                    |
| ------------------------------------------------------------------- |
| The system shall allow the user to upvote a question in the system. |

| System Requirement                                                                            |
| --------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to upvote the question by pressing the upvote button.       |
| 2. The system will check the question against the database.                                   |
| 3. If the question is found, the system will add 10 reputation points to the question's user. |

### Downvote Question

| User Requirement                                                      |
| --------------------------------------------------------------------- |
| The system shall allow the user to downvote a question in the system. |

| System Requirement                                                                                |
| ------------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to downvote the question by pressing the downvote button.       |
| 2. The system will check the question against the database.                                       |
| 3. If the question is found, the system will remove 2 reputation points from the question's user. |
| 4. If the question is not found, the system will show an error message.                           |
| Pre-conditions:                                                                                   |
| - User must press the downvote button.                                                            |
| Post-conditions:                                                                                  |
| - The question's user will lose 2 reputation points if the question is valid.                     |
| - The system will show an error message if the question is not valid.                             |

### Search Questions

| User Requirement                                                       |
| ---------------------------------------------------------------------- |
| The system shall allow the user to search for questions in the system. |

| System Requirement                                                                         |
| ------------------------------------------------------------------------------------------ |
| 1. The system will allow the user to enter the search query.                               |
| 2. The system will retrieve all questions that contain the search query from the database. |
| Pre-conditions:                                                                            |
| - User must type the search query.                                                         |
| Post-conditions:                                                                           |
| - The system will display all questions that contain the search query.                     |

### Search Users

| User Requirement                                                   |
| ------------------------------------------------------------------ |
| The system shall allow the user to search for users in the system. |

| System Requirement                                                                     |
| -------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the search query.                           |
| 2. The system will retrieve all users that contain the search query from the database. |
| Pre-conditions:                                                                        |
| - User must type the search query.                                                     |
| Post-conditions:                                                                       |
| - The system will display all users that contain the search query.                     |

### Search Tags

| User Requirement                                                  |
| ----------------------------------------------------------------- |
| The system shall allow the user to search for tags in the system. |

| System Requirement                                                                    |
| ------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the search query.                          |
| 2. The system will retrieve all tags that contain the search query from the database. |
| Pre-conditions:                                                                       |
| - User must type the search query.                                                    |
| Post-conditions:                                                                      |
| - The system will display all tags that contain the search query.                     |

### View Tags

| User Requirement                                                |
| --------------------------------------------------------------- |
| The system shall allow the user to view all tags in the system. |

| System Requirement                                         |
| ---------------------------------------------------------- |
| 1. The system will retrieve all tags from the database.    |
| 2. The system will display the tags' names and reputation. |
| Pre-conditions:                                            |
| - User must be logged in.                                  |
| Post-conditions:                                           |
| - The system will display all tags in the system.          |

### Edit Question

| User Requirement                                                              |
| ----------------------------------------------------------------------------- |
| The system shall allow the user to edit questions information if he eligible. |

| System Requirement                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------- |
| 1. The system will allow the user to enter the question's title, description and tags.                                           |
| 2. The system will check the title against the database.                                                                         |
| 3. If the title is found and the user has Privileges to edit, the system will update the question's information in the database. |
| 4. If the title is not found or the user has no Privileges to edit, the system will show an error message.                       |
| Pre-conditions:                                                                                                                  |
| - User must type the question's informations.                                                                                    |
| - User must have Privileges to edit the question.                                                                                |
| Post-conditions:                                                                                                                 |
| - The question's information will be updated in the database if his information is valid and user has Privileges.                |
| - The system will show an error message if the question's information is not valid or user has no Privileges.                    |

