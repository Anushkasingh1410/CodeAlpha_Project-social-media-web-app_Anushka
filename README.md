
### Pages

- Login Page
- Signup Page
- Create Profile Page
- Edit Profile Page
- Create Post Page
- Delete Post Page
- Update post page
- Password Reset Page
- Feed/Home page
- User Profile Page
- Search Results Page
- Post Comment Page

### Features

- Follow/Unfollow Users
- Like/Unlike the posts
- Download the post images
- Comment on user posts
- User suggestion section
- Search users through the search bar

### Tools and Techs

Backend Framework: `Django`
<br/><br/>
Front-end : `Bootstrap, SCSS, HTML,CSS, Javascript`
<br/><br/>
Database: `Sqlite3`
<br/><br/>

   If u don't have a virtualenv installed

   ```bash
   pip install virtualenv
   ```
   **For Windows Users**
   ```bash
   virtualenv env
   env/Scripts/activate
   ```


   **For Linux Users**
   ```bash
   virtualenv env
   source env/Scripts/activate
   ```

   If you are giving a different name than `env`, mention it in `.gitignore` first

3. Install all the requirements

   ```bash
   pip install -r requirements.txt
   ```

    ```bash
   cd socials
   ```


4. Make migrations/ Create db.sqlite3

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Create a super user.
   This is to access Admin panel and admin specific pages.

   ```djangotemplate
   python manage.py createsuperuser
   ```
   

   Enter your username, email and password.



