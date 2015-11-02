# PlanktonBloomsStudy
Files associated with the computational experiment resulting in Smith et al., "Inferred support for disturbance‐recovery hypothesis of North Atlantic phytoplankton blooms", 2015

# Introduction
This mini user guide is aimed to help you get up and running with the computational experiment used in the publication  

Smith, M. J., D. P. Tittensor, V. Lyutsarev, and E. Murphy (2015), Inferred support for disturbance-recovery hypothesis of North Atlantic phytoplankton blooms, J. Geophys. Res. Oceans, 120, [doi](http://dx.doi.org/10.1002/2015JC011080) 

# Altai
The experiment was performed in the third generation of modelling environment (brief history: http://research.microsoft.com/en-us/projects/msrceesdm/default.aspx) being developed by the Computational Science Laboratory of Microsoft Research. This link takes you to the download page for that version of the modelling environment: http://research.microsoft.com/en-US/projects/msrceesdm/altai.aspx. It is important to follow the installation guidelines on that download page, including the prerequisites.

# Connecting to the .git repository
Launch the application and click "local host"
Then click "open remote git repository…"
Then paste "https://github.com/predictionmachines/PlanktonBloomsStudy.git" into the box labelled "enter git repository URI:" and click OK. 

The screen freezes for a bit and then…

You should be greeted with a screen entitled "make chart PosteriorSimulationSite5" with a colourful graph on the right hand side. If you get this far then you have successfully connected the Altai project to the computational experiment. We left the experiment with that view so that visitors immediately see some model predictions compared to data. The data is for bin NA-5, in grey, and the model predictions are for Models 1 and 2 with bin-specific and bin-shared parameters.

If you now click "Home" in the top right hand corner then you will get to the main screen for beginning any further investigations into the experiment or making changes for yourself. Note that you will not be able to check in any changes into the root GIT repository. If you do wish to make changes you will need to create a fork of the git repository into your own GitHub account and connect Altai to that.

The "Home" screen lists all of the objects that were created and actions that were performed during the course of the computational experiment. The top right corner contains a text box to help you search for objects or actions. For example, if you want to fund the source code for the two models used in the paper, named Model 1 and Model 2 in the paper, then these can be found by searching for "Compile F# NPZModel" and "Compile F# NPZModel2", respectively. Clicking on either of the search results that are labelled as specified here will take you to the F# code that specifies the models that were used in the study. 

