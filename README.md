# **Middleware**

**_Error handling_** is a middleware that handles if an error occurs in the synchronous code. For more information [click here](http://expressjs.com/en/guide/using-middleware.html#middleware.error-handling). 

**_Bodyparser_** is a built-in middleware to create a content in the body to match the request header. For more information [click here](https://www.npmjs.com/package/body-parser). 



## **_Templating engines_**
---------------------------

Templating engines allow us embedding some Data and Javascript code into a HTML code. We start by installing ejs package json and we include this code: 

>< %= the property name of the object and some javascript code %> 
>
>app.get('/', function (req, res) {res.render('index', { title: 'Hey', message: 'Hello there!' })}).

### **HTTP Status Codes**
---------------------------
There are many number of status: 

1. 100 status is **continue**.
2. 200 status is **OK** which mean that the request is successful.

To learn more [click here](https://httpstatusdogs.com/). 


### **HTTP verbs**
------------------

There are several request methods, here are the most commonly used: 

- Post
- Get
- Head 
- Put
- Delete

To Know more about those request methods [click here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods).

#### **HTTP headers**
---------------------

*HTTP Header* are used to add additional information along the request or the response. For more information [click here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers).