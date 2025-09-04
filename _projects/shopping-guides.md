---
title: Shopping Guides Categorization
meta: Amazon · 2025
order: 1
summary: Using LLMs, embeddings and Louvain's algorithm to group Shopping Guides for display on Homepage.
---
*New York, NY | May – Aug 2025*  
**Tech stack:** Python, pandas, Louvain, LLMs & embeddings  

This summer, I was back with the team I worked with the previous summer! I worked on developing ingresses to [Shopping Guides](https://www.amazon.com/guide), generative AI–powered guides that explain a product type and suggest relevant recommendations to customers. These guides were shown through widgets on the Amazon Homepage, but there wasn’t a proper system to categorize them. Everything was done manually, and as a result, only about 40% of guides were organized.  

To solve this, I built a pipeline that combined large language models with embeddings to **cluster and title more than 600 guides**. What once took a full week of manual effort could now be done in **under six hours**, and coverage jumped from **40% to 75%**.  

I also used LLMs to generate category names automatically, making it easier for customers to navigate and discover products.  

Throughout the project, I led design reviews with engineers, applied scientists, and senior leadership to align on the solution and ensure its impact.  

Here's an example of what my work will look like on the Amazon mobile app:
<p align="center">
  <img src="/images/categoriesex.png" alt="Shopping Guide example" width="300"/>
  <br/>
</p>

