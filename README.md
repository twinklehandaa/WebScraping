# Web Scraping
Web scraping is a useful technique for extracting data from websites. **Beautiful Soup** is a Python library that makes it easy to parse HTML and XML documents. Essentially, it takes a messy web page and turns it into a structured object that you can easily navigate and extract data from. We use it to sift through the HTML code of websites and find the specific information we need.
## Key Beautiful Soup Methods Explained

* **`prettify()`:**
    * Formats the parsed HTML/XML into a readable string with indentation.
    * Useful for debugging and inspecting the document structure.
* **`find_all()`:**
    * Finds all elements matching the specified criteria (tag, attributes).
    * Returns a list of matching elements.
    * Returns an empty list if no matches are found.
* **`find()`:**
    * Finds the first element that matches the specified criteria.
    * Returns the matching element, or `None` if not found.
* **`select()`:**
    * Uses CSS selectors to find elements.
    * Provides a powerful and flexible way to target elements.
    * Returns a list of matching elements.
