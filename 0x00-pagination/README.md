This repository contains code for implementing pagination in web applications.

Usage
To use pagination in your project, follow these steps:

Clone the repository to your local machine:
Include the pagination module in your project.

Implement pagination in your views or controllers as needed, using the provided functions.

Functions
paginate(data, page_size, current_page): This function takes the data to be paginated, the page size, and the current page number as input parameters, and returns the paginated data.

get_page_count(data, page_size): This function calculates the total number of pages based on the total number of items and the specified page size.

generate_page_links(total_pages, current_page): This function generates HTML links for navigating through the pages.
