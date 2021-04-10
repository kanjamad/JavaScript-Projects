

An asynchronous function can run at any time independently and it won't stop the browser from completing the loading of a page.


!!!
So that means by default, if we did not do asynchronous and we did not do await, it would try toset this response value before it had a chance to fetch and that would cause an error.

So in this case, we're only setting the response constant when we actually have data and it can actually be set.
Or else it would just be undefined.




### Additional Resources
1. <a href="https://www.heropatterns.com/" target="_blank">Hero Patterns</a>
2. <a href="https://type.fit/api/quotes" target="_blank">Inspirational Quotes</a>
3. <a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent" target="_blank">Tweet button</a>
4. <a href="https://www.w3schools.com/howto/howto_css_loader.asp" target="_blank">CSS Loader</a>