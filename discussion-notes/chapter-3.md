# Chapter 3 discussion #  
- Functional Developers think in terms of ACD.  In what terms might a business owner/product owner think? 
  - Events (actions) and Data perhaps?  User fills in loan amount field and presses submit.
- Or can users be trained to see calculations, like the fridge example demonstrates?
- Our EDE users definitely think in terms of calculations. 

Page 36 - Point 3. Calculations can be composed of smaller calculations and data - Can you think of an example where data might be hidden in our shopping cart?  Eggs cannot be purchased individually. 

"Data is facts about events" - Is this true in OOP?  How do we think about data in OOP?  In OOP, data and its corresponding calculations might be coupled.  In functional the coupling is broken.  Is this good or bad and why?  OOP has better protections for the data.  Whereas Functional makes it easier to interpret the data in different ways. 

Did the coupon email exercise help clarify ACD for you? 

Did you come up with different ideas on how the logic could be broken down for coupon emailer? 

**SPOILER QUESTIONS below**

Page 52 - Did you notice the potential for a performance/memory problem before the book mentions it?  Are there other angles that could handle the potential memory issue? 

How does ACD thinking affect your tests?   

Page 54-56 - Actions _spreading_... thinking about some legacy code you might have worked on... did the code also have symptoms of Action spreading?  For me this happens when I inject my Data Access into my Business layer as an interface.  Did I cause Actions to spread or did I side-step the Action spreading by using an interface?  What would the app look like if I retrieved data before calling into the Business Layer?