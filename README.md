## DATA

Users
-PK user_id
-user_name
-user_password

comments
-PK comment_id
-FK post_id
-create_date
-user_name
-text


Posts
-PK post_id
-FK user_id
-FK subject_id
-rate (similar to reddit)
-like/save
-picture
-external link

Subjects
-PK subject_id
-subject_name
-subject_info

## USER STORIES

