## UGScholar base folder

This folder is to be used to initialize the UGScholar website.


## Installation

This project requires the installation of composer and doctrine orm. 
(https://getcomposer.org/download/) to install composer.
(https://www.doctrine-project.org/projects/doctrine-orm/en/2.11/tutorials/getting-started.html) for a more detailed guide on setting up doctrine orm. 

## Usage

# database config
Navigate to bootstrap.php in lines 19-24 to change database configurations.

# database classes
Since this is a model first approach, all classes must be modelled in the src folder using appropriate metadata language.

# database class example
a file at C:\Users\dines\OneDrive\Desktop\UGScholar\src\model\database\test\Product.php
was created to test database operations.

# saving changes through doctrine orm
run the following commands in the terminal:
vendor/bin/doctrine orm:schema-tool:drop --force
vendor/bin/doctrine orm:schema-tool:create
or you can use the update command:
vendor/bin/doctrine orm:schema-tool:drop --force
vendor/bin/doctrine orm:schema-tool:create