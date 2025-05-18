# Web Development Core Concepts

## HTTP Methods & Status Codes

### HTTP Methods
- **GET**: Retrieves data from a server
- **POST**: Submits data to be processed
- **PUT**: Updates existing data
- **DELETE**: Removes data

### HTTP Status Codes
- **2xx Success**
  - 200: OK
  - 201: Created
- **3xx Redirection**
  - 301: Moved Permanently
  - 304: Not Modified
- **4xx Client Error**
  - 400: Bad Request
  - 401: Unauthorized
  - 403: Forbidden
  - 404: Not Found
  - 405: Method Not Allowed
  - 409: Conflict
- **5xx Server Error**
  - 500: Internal Server Error
  - 502: Bad Gateway
  - 503: Service Unavailable


## CSS Selectors
- **Class Selector**: `.class-name`
- **ID Selector**: `#id-name`
- **Element Selector**: `div`, `p`, `h1`
- **Attribute Selector**: `[type="text"]`
- **Pseudo-class Selector**: `:hover`, `:active`, `:focus`
- **Pseudo-element Selector**: `::before`, `::after`
- **Descendant Selector**: `div p`
- **Direct Child Selector**: `div > p`
- **Sibling Selector**: `div + p`
- **Next Sibling Selector**: `div ~ p`
- **Universal Selector**: `*`

## Git Basics
- `git init`: Initialize a new repository
- `git add`: Stage changes
- `git commit`: Save staged changes
- `git push`: Upload commits to remote
- `git pull`: Download and merge changes
- `git clone`: Copy repository
- `git branch`: Create/switch branches

## JavaScript Concepts

### Callbacks & Higher-Order Functions
- Callback: Function passed as argument
- Higher-Order Function: Function that takes/returns functions

### Array Methods
- `filter()`: Create new array with filtered elements
- `map()`: Transform array elements
- `forEach()`: Execute function for each element
- `push()`: Add element to end
- `pop()`: Remove last element
