# SalespersonTracker
### A micro-app to track how many guests each salesperson is working with right now.

Every now and then, a car dealership receptionist needs to keep track of things. This time, it was a busy day and I needed to know quickly if there were any salespeople potentially available to work with guests who were walking in. Yes, in Spring 2020. 

I originally added a <div> to my Managers and More Pegboard for salespeople but I couldn't track enough. I needed to know:
  - Who wasn't there at all
  - Who was there but had no guests
  - Who had one guest and could maybe take another
  and
  - Who had two guests already and couldn't take another
  
Clearly, three colors weren't enough. I originally tried adding in the mouse wheel button and may get back to that someday with a function that can capture which mouse button was used on which CSS button by id, but I needed a solution quickly.

So I added in an event listener for mouse over to the single and double click options and picked colors with an eye to accessibility.

Now the default is a grey "person is not even here". A user can mouse over to mark the person as present in the building (blue), single click for one guest (gold), and double click for two guests (garnet).

Again, I am not part of the IT department and do not have permission to access much on my work computer. My goal was to make my life a **little** easier without breaching the company's security. Without access to jQuery or Bootstrap, the result is not the prettiest page in the world but functional, responsive, and likely usable on many browsers. Side note: I have indeed changed the names of my co-workers to Clue characters.

Please see the product [here.](https://carmelvineyard.github.io/SalespersonTracker/index.html)
