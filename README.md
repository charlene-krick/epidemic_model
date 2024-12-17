# Epidemic model of RSV virus 
## Abstract
In this project, we propose to study an age-structured mathematical model for respiratory syncytial virus where we will focus on people over 50 years old. Real data on hospitalized people over 50 years old in the Spanish region of Valencia were used in order to determine some seasonal parameters of the model.
Weekly predictions of the number of adults older than 50
years old that will be hospitalized in the following years in Valencia are presented using this model. Results
are applied to estimate and discuss about vaccination strategies.

## Introduction
Here, Respiratory Syncitial Virus (RSV) is studied among the older people.
It is only recently that the impact of RSV on adults has been studied, as up to 18% of the pneumonia
hospitalizations in patients older than 65 years old are due to RSV. 

In Spain, there are 15 000-20 000 visits to primary care due to RSV each year.
RSV is the cause of annual seasonal epidemics with minor variations each year and its coincident oc-
currence with other widespread viral infections such as influenza or rotavirus, produces a high number of
hospitalizations overstretching the health service. Moreover, it is easily transmitted and nosocomial infections are frequent.

Therefore, research on RSV and other viruses and the development of strategies to control epidemics are
important from both the sanitary and economic point of view.
Mathematics models have been shown to be a powerful tool to analyse the epidemiology of infectious
illness, to understand their behaviour, to predict their social impact and to discover how external factors
change the impact of disease. In the case of RSV, the building of a reliable model is a priority objective to
predict the medical care requirements needed in the following seasons.

Although human respiratory syncytial virus (RSV) is an important cause of illness and death in older
adults, no RSV vaccine has been licensed. However, vaccine have been developed and proved safe over
several studies. This vaccine might be available in the near future and, consequently, planning of vaccination
strategies is urgently required.

## Mathematical model
We introduced an age-structured SLIRS model with two age groups : the first one (i=1) corresponds to the
people aged 0-50 years old and the second one (i=2) corresponds to the adults older than 50 years old.
This is justified because the disease is more acute in adults older than 50 years old, as confirmed by hospita-
lization data. For each age group, we have four subdivisions according to the state of the individuals with
respect to the disease :
-  Susceptibles Si (t ), i = 1, 2 : the number of those at risk of contracting the disease
-  Latents Li (t ), i = 1, 2 : the number of those contracting the disease but are not contagious yet.
-  Infectives Ii (t ), i = 1, 2 : the number of those infected and capable of transmitting the disease.
-  Recovered Ri (t ) , i = 1 , 2 : the proportion of those recovered from the disease that are temporarily
immune to re-infection.


In this model, it is assumed that there are some simplifying hypothesis :

-  Primary and secondary infections have the same rate of recovery and infectivity but it is not the case
in real clinical situations.
-  The mixing between the age group is homogeneous.

That is why, we consider a vaccination strategy for Valencia.

