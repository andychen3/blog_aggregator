# Blog RSS Feed Aggregator

Project Overview:
------------------------------------------------------------------------------------------
Developed a Go-based RESTful API enabling users to scrape and aggregate their preferred blog's RSS feed, providing a streamlined experience for reading favorite blog posts.


Learning Outcomes:
------------------------------------------------------------------------------------------
1. Learn how to use Go's http library.
2. Learn how to use goroutines
3. Learn about basic database migrations with Go and PostgreSql


Built with:
------------------------------------------------------------------------------------------
* Go
* PostgreSQL


Modules:
------------------------------------------------------------------------------------------
* Goose
* Sqlc
* Chi

Features:
------------------------------------------------------------------------------------------
* Performs CRUD operations to retrieve RSS feeds from blogs
* Spawns concurrent goroutines to fetch updates from multiple RSS feeds
* Follows and unfollows feeds
