# Speculator
---
## Motivator
From the subprime mortgage crisis of the 2000’s to the marked volatility of Tesla stock over the entirety of its lifespan, its no secret that much of what drives stock prices is purely emotional and not backed by facts. This is supported by the fact that a key determinant of stock prices is the general population's expectations for the trajectory of those very stock prices, in accordance with elementary financial theory. <sup>[1]</sup> We can do better in 2020. 

## Approach
This web-app will use sentiment analysis to scrape a curated twitter feed from a selection of reliable news sources to create a holistic view of a company’s public opinion and relevant analysis of political, economic, social, and technological factors. It will then utilize <put decided upon financial info api here> to analyze a company's key financial statements—-statement of financial position, statement of comprehensive income, statement of cash flows—-to assess the company's financial health.
Finally, it will assess the competency of management by comparing their publicly available CVs to exceptional industry leaders.

## Tech Stack

### UI/UX
- Figma
```
Splash Page: https://www.figma.com/file/VSdWxbEuMj0RmnQYyikmu2/Splash-Page?node-id=0%3A1
Securities Page: https://www.figma.com/file/vQyaqk1zYBWpSU5r6SU9ae/Securities-Landing-Page?node-id=0%3A1
```

## Languages, Frameworks, and Tools
- React for programmatic front-end
- GCP Cloud Natural Language API for sentiment analysis
- Kaggle, SEC Edgar API for financial data
- Twitter API for semantic data
- MongoDB, ExpressJS, and NodeJS for backend business-logic server


### References
<sup>1</sup> https://www.investopedia.com/articles/basics/04/100804.asp
