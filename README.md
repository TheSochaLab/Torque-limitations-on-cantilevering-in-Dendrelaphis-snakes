# Torque-limitations-on-cantilevering-in-Dendrelaphis-snakes
Files for Torque limitations on cantilevering in Dendrelaphis snakes paper in JEB\
Citation: [Graham, M., Astley, H. C., Clemente, C. J., & Socha, J. J. (2026). Torque limitations on cantilevering in Dendrelaphis snakes. Journal of Experimental Biology, jeb-251396.](https://journals.biologists.com/jeb/article-abstract/doi/10.1242/jeb.251396/372318/Torque-limitations-on-cantilevering-in?redirectedFrom=fulltext).

The code for this paper has two components.

* code already used for analysis in previous work, which was used to process trajectory data and calculate relevant distances. You can find those materials [here](https://github.com/TheSochaLab/FlyingSnakeGaps) (for the Chrysopelea paper) and [here](https://github.com/TheSochaLab/DendrelaphisGaps) (for the Dendrelaphis paper). These correspond to analyses completed for the following papers: 
  * [Graham, M., & Socha, J. J. (2021). Dynamic movements facilitate extreme gap crossing in flying snakes. Journal of Experimental Biology, 224(20), jeb242923.](https://journals.biologists.com/jeb/article/224/20/jeb242923/272554/Dynamic-movements-facilitate-extreme-gap-crossing)
  * [Graham, M., & Socha, J. J. (2023). Dynamic gap crossing in Dendrelaphis, the sister taxon of flying snakes. Journal of Experimental Biology, 226(19), jeb245094.] (https://journals.biologists.com/jeb/article/226/19/jeb245094/333433/Dynamic-gap-crossing-in-Dendrelaphis-the-sister)
* new code/analyses for this paper. These include analyses for the morphology of the relevant individuals, applying the equation from [Astley, 2020](https://academic.oup.com/icb/article-abstract/60/1/140/5811566), and analyzing failure-like behavioral patterns.
  
Summary by analysis: 
* Scaling across body size in Dendrelaphis - Figure 4 folder (code performs the analysis and creates the figure)
* Pitching predictions - Figure 5 folder contains the Dendrelaphis and Chrysopelea data and the code to analyze the location of the COM and generate the figure. 
* Buckling predictions - Astley_equation_analysis.ipynb has the morphological data we referenced and uses the equation in Astley, 2020 to generate predicted buckling distances
* Behavioral analyses - the Figure 6 folder contains the code to create the figures, and the csvs that contain the behavioral categorizations by trial. The code also references chrysopelea datasets that are NOT in the file - they can be found at the first link above, the previous Chrysopelea paper. 
