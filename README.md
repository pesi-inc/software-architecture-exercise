# Introduction

These exercises are expected to take around 2 hours in total. However, time spent is not part of our assessment. Please work at your own pace in whatever environment is most comfortable for you. If you have any questions, please reach out to us!
 
# Exercise 1
 
Write 2 functions (each with a different implementation) which accept a string and return a string containing the same characters as the input string -- but in a random order. Compare these implementations and describe why you might prefer one implementation over another (and under what circumstances).

## Deliverables
- Source file(s) in the language of your choice
- A narrative comparing your implementations

Preferred delivery is via public Git repository (e.g. GitHub).
 
# Exercise 2
 
You've been asked to architect a new web-based e-commerce system. Our stakeholders have given us the following requirements:
 
- Customers must be able to search for products by keyword and a host of other product attributes (brand, category, price range, product type)
- Customers must be able to pay with a credit card (our stakeholders have been non-specific about any type of payment processor; you have latitude to suggest)
- After checking out, customers must be emailed a receipt with a summary of their order
 
In addition to these requirements, our stakeholders have suggested the system must demonstrate the following qualities:
 
- Scalability (e.g. receiving a 50x traffic boost during large, seasonal sales)
- Performance (particularly when customers are searching for products)
- Affordability (the business is concerned about over-paying for idle compute resources and inefficient database usage)
 
Finally, our technical team has identified the following risks:
 
- Our transactional email processor can have high latency, which can lead to seconds long waits when sending emails
- If we don't have visibility into performance and error rates, we won't be able to respond to application issues in a timely manner
 
Your task is to create a design document for this system which satisfies stakeholder requirements, demonstrates the given desired qualities, and seeks to mitigate the technical risks our team has identified.

## Deliverables
 
- A diagram with your proposed architecture (for a rough idea of scope, a single page diagram with ~8-10 boxes)
- A narrative describing your architectural choices as they relate to requirements, qualities, and technical risks (for a rough idea of length, ~2-3 paragraphs)
- No code is required to be written for this exercise

Preferred delivery is via email attachment.