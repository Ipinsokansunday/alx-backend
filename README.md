Resources
To fully understand the concepts covered in this project, you should review the following materials:

REST API Design: Pagination:

This resource explains how to paginate datasets in RESTful APIs, covering the basics of pagination and different techniques for implementing it.
HATEOAS (Hypermedia As The Engine Of Application State):

HATEOAS is a constraint of REST API that keeps the RESTful API client decoupled from the server. This resource will help you understand how to implement hypermedia-driven APIs.
Learning Objectives
By the end of this project, you should be able to:

Paginate a Dataset with Simple page and page_size Parameters:

Understand how to split a dataset into smaller chunks and navigate through them using page (current page number) and page_size (number of items per page) parameters.
Paginate a Dataset with Hypermedia Metadata:

Learn how to enhance your API responses with hypermedia metadata that provides navigational links to other pages, making the API more self-descriptive and easier to use.
Paginate in a Deletion-Resilient Manner:

Understand how to ensure that pagination remains consistent even when records are deleted from the dataset. This typically involves techniques like cursor-based pagination or other strategies that do not rely on fixed offsets.
These concepts are crucial for creating scalable, user-friendly APIs that can handle large datasets efficiently while remaining robust and flexible in the face of changes to the underlying data.
