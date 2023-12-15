## Class-13 Reading Notes

- Why would a developer use local storage for a web application?

  - Decrease number of Web service calls per hour
  - Simplicity for maintaining the state of an interface, i.e. entire HTML, objects, etc.
  - Faster loading speeds
  - Provide users with some degree of offline capability 

- What information should not be stored in local storage?

  - Sensitive data- passwords, addresses, authentication information
  - Large amounts of data
  - Temporary data- local storage is for persistent data

- Local storage can store what type of data? How would you convert it to that type before storing?

  - Data Types can be stored in local storage, i.e. objects, arrays, etc. However, they must be stored in a string and can be converted to one using `JSON.stringify()` and converted back using `JSON.parse()`.
