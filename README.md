# Census-Income-Prediction-Project


Problem Statement :

    This data was extracted from the 1994 Census bureau database by Ronny Kohavi
    and Barry Becker(Data Mining and Visualization, Silicon Graphics).
    A set of reasonably clean records was extracted using the following conditions
    ((AAGE>16)&&(AGI>100)&&(AFNLQGT>1)&&(HRSWK>0)).
    
    
    In the dataset Income is the target variable which has 2 classes so it termed 
    to be s Classification Problem . Here the preddiction task is to determine 
    whether a person makes over $50k a year.
 
     Description of fnlwgt(final weight) The weights on the Current Population Survey
     (CPS) files are controlled to independent estimates of the civilian noninstitutional 
     population of the US. These are prepared monthly for us by Population Division here 
     at the Census Bureau. We use 3 sets of controls.
     These are :
     
     A single cell estimate of the population 16+ for each state.
     
     Controls for Hispanic Origin by age and sex.
     
     Controls by Race, age and sex.
     
     
    We use all three sets of controls in our weighting program and "rake" through
    them 6 times so that by the end we come back to all the controls we use. The 
    term estimate refers to population totals derived from CPS by creating  
    "weighted tallies" of any specified socio-economic characteristics of the 
    population. People with similar demographic characteristics should have similar 
    weights. There is on eimportant caveat to remember about this statement . That
    is that since the CPS sample is actually a collection of 51 stats samples each 
    with its own probability of selection, the statement only spplies within state.
