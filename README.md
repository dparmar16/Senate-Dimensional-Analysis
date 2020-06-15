# Senate-Dimensional-Analysis
The purpose of this analysis is to look at the political positions of US senators in a geospatial method.

Typically, US politics is thought of in a two dimensional framework, with politicians being liberal/conservative on both social and economic issues. However, with the realignment brought on by the Trump Administration, there has been a movement toward isolationism and protectionist policies that don't fit traditional economic conservatism.

I wanted to include this "third dimension" of globalism/isolationism and how existing US Senators fit in that model. Using geospatial analysis of voting records, I could see how close Senators were to each other and cluster them in groups.

The three dimensions are:
- Fiscal issues, which I represented through the [Club for Growth score](https://www.clubforgrowth.org/scorecards/app/?party=all&chamber=S&yr=2019&state=all&rep). Note that I had to invert the score because higher meant more conservative.
- Social issues, which I represented through the  [ACLU score](https://www.aclu.org/scorecard/?filter=all).
- Global issues, which I represented through the [NumbersUSA score](https://www.numbersusa.com/content/my/tools/grades/list/0/CONGRESS/US/S/Grade/Active). NumbersUSA advocates for lower immigration to the US, so I had to invert the score to make it progressive.

I gathered this data manually then plotted it using the scatter3D function within the matplotlib library. I then used [Ben Alex Keen's writeup](https://benalexkeen.com/k-means-clustering-in-python/) to manually find the clusters.

Enjoy, and feel free to reach out with any comments or questions.
