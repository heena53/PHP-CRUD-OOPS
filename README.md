# PHP-CRUD-OOPS

Our demo is about creating a simple PHP OOP CRUD app. You can use this knowledge in your current or future projects.

We use Bootstrap so that our application will have a decent UI.

I’m writing this tutorial with a clear goal: to give the best PHP OOP CRUD tutorial for beginners. I welcome your comments and suggestions to help me achieve this.

we will learn object oriented programming with PHP & MySQL.

git clone https://github.com/heena53/PHP-CRUD-OOPS.git

There are steps to follow:

Step-1: DATABASE TABLE STRUCTURE
	- Products Table
		-- Table structure for table `products`
			CREATE TABLE IF NOT EXISTS `products` (
			  `id` int(11) NOT NULL AUTO_INCREMENT,
			  `name` varchar(32) NOT NULL,
			  `description` text NOT NULL,
			  `price` int(11) NOT NULL,
			  `category_id` int(11) NOT NULL,
			  `created` datetime NOT NULL,
			  `modified` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
			  PRIMARY KEY (`id`)
			) ENGINE=MyISAM  DEFAULT CHARSET=latin1 AUTO_INCREMENT=38 ;


	- Categories Table
		-- Table structure for table `categories`
			CREATE TABLE IF NOT EXISTS `categories` (
			  `id` int(11) NOT NULL AUTO_INCREMENT,
			  `name` varchar(256) NOT NULL,
			  `created` datetime NOT NULL,
			  `modified` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
			  PRIMARY KEY (`id`)
			) ENGINE=MyISAM  DEFAULT CHARSET=utf8 AUTO_INCREMENT=4 ;


Step-2: CREATE THE TEMPLATE FILES
		- header.php
		- footer.php

Step-3: Download jQuery, Bootstrap, and Bootbox.js / Put live cdn url for that

Step-4: CREATING RECORD IN PHP THE OOP WAY (Create a file: create_product.php)

Step5-: Create the Database Configuration Class(Create a file: database.php)

Step-6:  Create the Object Class for Categories (objects/category.php)

Step-8: Create the Object Class for Products (objects/product.php)

Step-9: READING AND PAGING RECORD IN PHP THE (index.php , paging.php)

Step-10: UPDATING RECORD IN PHP THE OOP WAY (update_product.php)

Step-11: READ ONE RECORD IN PHP THE OOP WAY (read_one.php)

Step-12: DELETING RECORD IN PHP THE OOP WAY (delete_product.php )

Step-13: SEARCH RECORDS IN PHP THE OOP WAY (search.php )

Step-14: Create read_template.php (read_template.php)

Step-15 :Create core.php in “config” folder



 

