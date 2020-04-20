# ML_Design_Computing
Web scrapers here on this repository are developed for the course Machine Learning in Architecture at ITU Design Computing 2019-2020 Spring.

<h1>'yokAtlas'</h1> 
  <b>yokAtlas</b> is a scraper project to gather information from Council of Higher Education (CoHE) of Turkey website. The scraper is right now just optimized to get the information related cities where the every student is admitted from to each bachalor degree in Turkey, and related countries.
  <h2>How it works:</h2>
The scraper queries for all the universities in the system, and collects the links for each bachalor degree's links from the site. The links are a way to get into the programs' website, but sending too much responses to the direct website causes a block out, so the scraper sends requests related to the spesific information about the cities and the numbers of student admitted to that bachelor programme and the percentages. For that it generates the query spesificly. However, that specific code for this query can be modified to gather the other information shared at programme's website.
(in the code, the annotations are not well defined, so forgive me for that. I'm planning to implement them soon)


<h1>brutalScrape</h1>
  <b>brutalScrape</b> is a scraper designed to get the images at 'SOSBrutalism'dotcom. The aim of this project is to create a GAN model to transfer styles of regular architectural works from all around the world to brutalist architecture.
  <h2>How it works:</h2>
  This is an ongoing project
