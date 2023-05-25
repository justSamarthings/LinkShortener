# LinkShortener
C++ project of link shortener

URL shortening is used to create a unique shorter alternative for long URLs. These save a lot of space while storing, displaying on a website, or messaging. Once clicked on a short URL, it converts ID to URL and redirects to the original URL’s website. We convert each alphabet in URL to int and add it to the final URL ID. We have 62 possible chars i.e. A-Z, a-z, 0-9, if we can make a URL of length n, then we can have a total of 62^n URLs. 
One important thing to note is, the long URL should also be uniquely identifiable from the short URL. So we need a Bijective Function  
