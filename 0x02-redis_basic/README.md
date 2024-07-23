# Redis basic

This project contains tasks for learning to use the Redis NoSQL data storage application through Python3.

## Tasks To Complete

+ [x] 0. **Writing strings to Redis**<br/>[exercise.py](exercise.py)

+ [x] 1. **Reading from Redis and recovering original type**<br/>[exercise.py](exercise.py)

+ [x] 2. **Incrementing values**<br/>[exercise.py](exercise.py)
    
+ [x] 3. **Storing lists**<br/>[exercise.py](exercise.py) 
+ [x] 4. **Retrieving lists**<br/>[exercise.py](exercise.py) 

+ [x] 5. **Implementing an expiring web cache and tracker**<br/>[web.py](web.py) contains a Python script that meets the following requirements:
  + In this tasks, we will implement a `get_page` function (prototype: `def get_page(url: str) -> str:`). The core of the function is very simple. It uses the `requests` module to obtain the HTML content of a particular URL and returns it.
  + Start in a new file named [web.py](web.py) and do not reuse the code written in [exercise.py](exercise.py).
  + Inside `get_page` track how many times a particular URL was accessed in the key `"count:{url}"` and cache the result with an expiration time of 10 seconds.
  + **Tip**: Use [http://slowwly.robertomurray.co.uk](http://slowwly.robertomurray.co.uk) to simulate a slow response and test your caching.
  + **Bonus**: implement this use case with decorators.
