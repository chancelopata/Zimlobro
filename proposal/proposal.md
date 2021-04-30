# Big Data Proposal - Zimlobro

### Who is the client?

    Libraries interested in better understanding predicted demand for specific books. 




### Proposals on the sets of features we will need to develop from our base data.
    
    1. Average checkouts per title held -- Checkouts (from "Checkouts by Title") divided by ItemCount (from "Library Collection Inventory")
    
        a. Note: we may find that we can get more accurate measurement if we calculate this on multi-month basis, since checkouts will cross month boundaries.



### External data source ideas (links to data found would be great)

    1. Amazon and Abebooks both have seller APIs.  Supposedly, pricing information is available.  See:
     
     https://www.labnol.org/code/19882-amazon-api-php

     https://www.rainforestapi.com/?gclid=Cj0KCQjwsqmEBhDiARIsANV8H3ZO0mZ2D8dsqCcASkifv5eSa88UKnYECv9RvhWPpuQLZ_89tgQwKQkaAsf6EALw_wcB

    
    Note: Even with curent pricing available, predicting the optimal future time to sell a book would require us to build a database of prices that show change over time. 



### Details on the target/label you think we are predicting and how you will build that variable.

    Number of copies needed in the next 1, 2 and 3 months to optimally satisfy future demand.


### Ideas on how the client will use the tool.

    Clients could use the predictions to decide when to add additional copies of books growing in popularity and went to sell copies of books decreasing in popularity.



