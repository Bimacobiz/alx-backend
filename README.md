# 0x00. Pagination

## Overview
0x00. Pagination is a lightweight pagination library designed to simplify pagination implementation in web applications. It provides a convenient way to paginate data retrieved from a database or any other data source. This library is built with simplicity and flexibility in mind, aiming to streamline the process of integrating pagination into your projects.

## Features
- Simple and intuitive API for pagination.
- Support for various data sources including databases, APIs, and arrays.
- Customizable pagination settings such as page size and maximum number of pages.
- Seamless integration with popular web frameworks and libraries.
- Lightweight and minimalistic, ensuring minimal overhead.

## Installation
You can install 0x00. Pagination via npm:


## Usage
To use 0x00. Pagination, simply import it into your project and initialize a pagination instance with your data source and desired settings. Here's a basic example of how to use it:

```javascript
const Pagination = require('0x00-pagination');

// Your data source, e.g., an array of items
const data = [/* Your data */];

// Initialize pagination instance
const pagination = new Pagination(data, {
    pageSize: 10, // Number of items per page
    maxPages: 5 // Maximum number of pages to display in pagination controls
});

// Get the current page of data
const currentPageData = pagination.getCurrentPage();

// Get pagination metadata
const metadata = pagination.getMetadata();

console.log(currentPageData);
console.log(metadata);

