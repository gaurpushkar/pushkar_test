# pushkar_test
Generation of results :
<br>Please execute pushkar_assignment.py to reproduce the results. If you are running in jupyter please run pushkar_test.ipynb
<br>The folder name 'data' should be in same folder as code.
<br><br>
The production raster will be 'Production.tif' as output of question1.<br>
The output of question 2 will be 'Counrty level production.csv'<br>
The output of question 3 will be 'N_output1.tif' and 'Nitrogen_plot.pdf'<br>
The output of question 4a will be 'N_output_4a.csv'<br>
The output of question 4b will be 'Rel_btw_No_Nl.pdf'<br>

Software dependencies:
1.	Python
2.	Libraries
	<P><br>
  a.	Rasterio<br>
  b.	Geopandas<br>
  c.	Pandas<br>
  d.	Os<br>
  e.	Rasterstats<br>
  f.	Numpy<br>
  g.	Matplotlib<br>
  </p>
3.	Data must be located in folder name ‘data’ in unzipped format as provided. 

4 (C) : It is evident from data that Nitrogen loss and NUE are inversely proportional, it can be further inferred that with increase in NUE the production of wheat crop will increase.
The pattern also shows that if the value of NUE if greater than 0.4 the mean value of production is 32.51 MT and mean of N loss is 0.55 MT, while if NUE is less than 0.4 the mean value of production is 63.24 MT and mean of N loss is 3.81 MT demonstrating a polarity in N loss and production values with respect to NUE.

5: The present analysis can be used as a sensitivity factor in estimation of wheat crop production for a region. The Nitrogen loss can be incorporated into EPIC model for calibration to produce final production estimates. 

6: Name was different in NUE file for USA and Russia.
