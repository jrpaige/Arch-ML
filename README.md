# Final Capstone Project Proposal


## What are you trying to do?
<i>Articulate your objectives using absolutely no jargon (i.e. as if you were explaining to a salesperson, executive, or recruiter). Again, this should be a description of a real world problem, not an algorithm you aspire to use.</i>

<b><u>Floorplan Layout Generator</u></b>

“Computers are not good at open-ended creative solutions; that’s still reserved for humans. But through automation, we’re able to save time doing repetitive tasks, and we can reinvest that time in design.”—Mike Mendelson

I plan to build and construct an automatic floorplan image analysis tool and/or a classification tool to classify the type of area/room within a layout and provide the percent that the area/room takes of the whole floor/space.

## How has this problem been solved before?
<i>If you feel like you are addressing a novel issue, what similar problems have been solved, and how are you borrowing from those? Note, at this point you should be citing papers, medium articles, or other sources from the data science community. You should have links to your research in your proposal document and cite previous work.</i>

Architecture's use of automation is on the rise. For instance, a company named [Finch](https://finch3d.com/) has built an algorithm which "generates different spatial configurations according to predetermined parameters as you change the total area of the space." [1] Another company HighArc is using machine learning to automate exterior home design. [2]

A graduate of Harvard University's School of Design has done a lot of interesting work and reporting on the convergence of machine learning and architectural design.[5]
Specifically, two of his projects aim to  "(1) generate floor plans i.e. optimize the generation of a large and highly diverse quantity of floor plan designs, (2) qualify floor plans i.e. offer a proper classification methodology" [3]

I think this has the best application to the work done in this DSI course thus far. 

## What is new about your approach, why do you think it will be successful?
## Who cares? If you're successful, what will the impact be?
<i> It's OK to be working on a problem that has been worked on before, but you do need to do need to have some novel contribution to the project.</i>
<i>It is preferable to be asked 'Who cares' now then when you're telling someone about your project. Not every project needs to change the world, but project whose appeal is very niche might not be the best way to spend your time and energy.</i>

Given Chaillou's work, I am not sure I have much to contribute. However, I do see this potentially playing a part in how houses are remodeled where the requirement of some spaces needing to stay can be restrictive on any new design. I also see this having an impact in a commerical environment where an entire office floor can be designed by the tool. It could further be used for parks/playgrounds, backyards, etc... 

Currently, I plan to get a firm grasp on mastering the interior floorplans of residential enviornments before moving onto the other possibiliies. 

## How will you present your work?
<i>Again, be ambitious in your proposals, but think about what is the most impactful way your project could exist.</i>

Here, the visuals will be the best storyteller. I propose to likely generate a site via https://pages.github.com/ which will allow for the mix of models, images, and storytelling. 

## What are your data sources? What is the size of your dataset, and what is your storage format?
<i> You should no longer be analyzing csv files. Is the amount of data you have limiting the ways you can approach the problem? Would you have a different approach if you could collect more? Same as last capstone, you should have all of your data on day one. </i>

A few options/resources have popped up in an initial search:

<b>CubiCasa5k</b><br>
https://zenodo.org/record/2613548#.XkrWShNKhTZ <br>
contains 5000 samples annotated into over 80 floorplan object catagories. 

<b>ROBIN (Repository Of BuildIng plaNs)</b> <br>
https://github.com/gesstalt/ROBIN <br>
170 - three bedroom floorplans<br>
170 - four bedroom floorplans<br>
170 - five bedroom floorplans

<b> SESYD "Systems Evaluation SYnthetic Documents</b><br>
http://mathieu.delalandre.free.fr/projects/sesyd/symbols/floorplans.html<br>
1000 images of various floorplans 


## What are potential problems with your capstone?
<i>More importantly, what is your plan to mitigate these problems? Again, being aware of previous solutions to similar problems gives you a template for successfully working with data of this type.</i>
## What is the next thing you need to work on?
<i>Getting the data, not just some, likely all? Understanding the data? Building a minimum viable product? Gauging how much signal might be in the data? </i>

Potential problems include Figuring out which data set to use and mastering image recognition through the use of neural networks. 
I plan to mitigate this by doing a lot of EDA into the data sets to decide ahead of time. 
In terms of beefing up my neural network/machine learning skills, I plan on scheduling time with my instructors outside of class as well as utilizing online resources to ensure a deep understanding of the tools. 

##### Citations

<b>1.</b> <br>
Baldwin, E. (2019). BuildTech Futures: Artificial Intelligence and Machine Learning. [online] ArchDaily. Available at: https://www.archdaily.com/924704/buildtech-futures-artificial-intelligence-and-machine-learning <br>
<b>2.</b>  <br>
Baldwin, E. (2019). Higharc Startup Aims to Automate Home Design. [online] ArchDaily. Available at: https://www.archdaily.com/918084/higharc-startup-aims-to-automate-home-design <br>
<b>3.</b>  <br>
Chaillou, S. (2020). AI & Architecture. [online] Medium. Available at: https://towardsdatascience.com/ai-architecture-f9d78c6958e0.<br>
<b>4.</b>  <br>
Chaillou, S. (2020). Space Layouts & GANs. [online] Medium. Available at: https://towardsdatascience.com/space-layouts-gans-19861519a5e9.<br>
<b>5.</b> <br>
Academia. (2019). Stanislas Chaillou. [online] Available at: https://harvard.academia.edu/StanislasChaillou.<br>

________________________

<b>As a backup plan, I would also be interested in classifying fashion/apparel images much like in the MNISK data set: </b>

https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset <br>
https://www.kaggle.com/nitinsss/fashion-dataset-with-over-15000-labelled-images <br>
https://zenodo.org/record/833051#.XkruARNKhTZ

