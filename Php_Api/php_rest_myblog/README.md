#### 1. First create database connection class (config/database.php)

#### 2. Create Model Post (model/post)

#### 3. Create Api (/api)
        - cors (allow origin) https://www.youtube.com/watch?v=PNtFSVU-YTI (default accept request from server itself)
        - config nginx ubuntu /var/www/html/Php/php_api/..
        https://stackoverflow.com/questions/10663248/how-to-configure-nginx-to-enable-kinda-file-browser-mode (enable autoindex to all file)
        
#### 4. Test Postman
        Read all
        - localhost/api/post/read.php
        Read one
        - localhost/api/post/read_single.php?id=1
        Create
        - localhost/api/post/create
            raw:{
                title 
                body
                author
                category_id
                }
        https://stackoverflow.com/questions/8207488/get-all-variables-sent-with-post
        - Update 

        

