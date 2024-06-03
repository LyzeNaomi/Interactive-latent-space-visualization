# Interactive-latent-space-visualization
This project is about an interactive visualization of models' latent spaces using Dash &amp; Plotly

*Email*: ***naomiewamba@ymail.com***

``` Press the play button to visualize our interactive dashboard.```

This dashboad follows from the work in this research paper [*Understanding Deep Learning for LoS prediction via Latent Space Visualization*](https://www.techrxiv.org/users/693475/articles/683131-understanding-deep-learning-for-los-prediction-via-latent-space-visualization) and conveys the following information:

1.	First, the landing page made up of 2 sections. 

a.	The left section: shows the 2D t-SNE projection of the LSTM model latent space. Each marker represents a patient from the test set and the maker’s color and shape is associated with their observed LoS (because it is retrospective data). 
  
  b.	The right section: entitled “ID MetaData” is a table with some demographic and admission information of all test patients. 
3.	Next, one can view the 2D projection of the latent space of 3 other models (GRU, Transformer and TCN) both in 2D & 3D. 
4.	Next, using the time slider entitled “Time Steps” one can view the latent space over time. That is, view the patients’ in the reduced prediction space over time. 
5.	Next, one can click on a patient on the interactive plot and the data of this patient gets highlighted in the table ID Metadata. 
6.	Next, one can click on a specific patient on the Table and this patient now gets highlighted on the plot (the size of the marker will increase) and view this specific patient over time in both dimensions.
7.	Next, one can select a group of patients on the plot and view frequency plots of this group. The frequency plots depend on a user-based feature selection. 




https://github.com/LyzeNaomi/Interactive-latent-space-visualization/assets/70583050/b6c7c4d0-f44d-4b85-951e-5fa972b4a0d4

