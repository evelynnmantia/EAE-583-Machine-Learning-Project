# Prediction of Maximum Hail Size Using a Random Forest Classifier

Authors: Izzy Smith and Evelynn Mantia

## I. Introduction and Background

Hail damage is a major cost to insurance companies across the United States, contributing to millions of dollars in repair costs each year to properties and crops (Brown et al. 2015). Specifically, hail is the costliest peril of severe convective storms (SCSs), causing an estimated $10 billion in property damages each year (Munich RE 2025). Despite the incredible impact hail has on society, current forecasting methods, both model driven and human produced, are unreliable in creating skillful and precise hail predictions (e.g., Adams-Selin et al. 2019; Blair et al. 2011; Burke et al. 2020; Gagne et al. 2017). Hail forecast methods can be verified using public (local) storm reports; these reports are subject to spatial biases associated with population density as well as reporting biases toward the inflation of hailstone sizes to reach severe thresholds (e.g., Allen and Tippett 2015; Changnon 1999; Doswell et al. 2005). 

There is a need for improved hail forecasting. Advancements toward improved hail forecasting can better prepare industries, like insurance and agriculture, to deal with anticipated damages. Also, new tools/research into more skillful hail forecasting can better equip forecasters to predict potential hail impact on society and encourage earlier and more accurate threat communication associated with hail. This project proposes to create a machine learning model that improves hail size predictability using Multi-Radar Multi-Sensor Maximum Estimated Size of Hail (MRMS MESH) and High Resolution Rapid Refresh (HRRR) variable datasets.  

While many studies have produced machine learning models to predict the probabilities of hail production, very few have looked at using machine learning for the estimation of hail sizes. For example, Burke et al. (2020) combined three different machine learning models using the HREFv2 dataset as input variables and compared their results with SPC’s practically perfect data and outlooks. This product was effective at reducing modeling bias and predicting hail probability and potential severity, as it was comparable to SPC’s practically perfect dataset; however, the model had a bias toward higher predicted hail sizes than were observed (Burke et al. 2020).  

Another study conducted by Gagne et al. (2017) produced a high-functioning machine learning model using data from two convective-allowing models (CAMs), including the Center for Analysis and Prediction of Storms’ (CAPS) Storm-Scale Ensemble Forecast system and the National Center for Atmospheric Research (NCAR) ensemble. Gagne et al. (2017) also used MRMS MESH data for hail size predictions, but noted that, despite this being the best available dataset for predicting hail size, it does show a large size bias. 

This project aims to build on previous literature dealing with machine learning and hail forecasting, not specifically for the overall probability of hail production, but by diving into the ability of a machine learning model to predict hail size. 

## II. Data and Methods


## III. Initial Results


## IV. Summary


## V. References

Adams-Selin, R. D., A. J. Clark, C. J. Melick, S. R. Dembek, I. L. Jirak, and C. L. Ziegler, 2019: Evolution of WRF-HAILCAST during the 2014–16 NOAA/Hazardous Weather Testbed Spring Forecasting Experiments. Weather and Forecasting, 34, 61–79, https://doi.org/10.1175/WAF-D-18-0024.1. 

Allen, J. T., and M. K. Tippett, 2015: The Characteristics of United States Hail Reports: 1955-2014. EJSSM, 10, 1–31, https://doi.org/10.55599/ejssm.v10i3.60. 

Blair, S. F., D. R. Deroche, J. M. Boustead, J. W. Leighton, B. L. Barjenbruch, and W. P. Gargan, 2011: Radar-Based Assessment of the Detectability of Giant Hail. EJSSM, 6, 1–30, https://doi.org/10.55599/ejssm.v6i7.34. 

Brown, Tanya M., et al. “Evaluating Hail Damage Using Property Insurance Claims Data.” Weather, Climate, and Society, vol. 7, no. 3, 1 July 2015, pp. 197–210, journals.ametsoc.org/view/journals/wcas/7/3/wcas-d-15-0011_1.xml, https://doi.org/10.1175/WCAS-D-15-0011.1. 

Burke, Amanda, et al. “Calibration of Machine Learning–Based Probabilistic Hail Predictions for Operational Forecasting.” Weather and Forecasting, vol. 35, no. 1, 23 Jan. 2020, pp. 149–168, https://doi.org/10.1175/waf-d-19-0105.1. 

Changnon, S. A., 1999: Data and Approaches for Determining Hail Risk in the Contiguous United States. J. Appl. Meteor., 38, 1730–1739, https://doi.org/10.1175/1520-0450(1999)038%3C1730:DAAFDH%3E2.0.CO;2. 

Doswell, C. A., H. E. Brooks, and M. P. Kay, 2005: Climatological Estimates of Daily Local Nontornadic Severe Thunderstorm Probability for the United States. Weather and Forecasting, 20, 577–595, https://doi.org/10.1175/WAF866.1. 

Escalating hail risk: Munich Re Specialty warns of billion-dollar threat | Munich Re - North America,. Accessed 18 November 2025, https://www.munichre.com/specialty/north-america/en/insights/climate-change-and-natural-disasters/escalating-hail-risk.html. 

Gagne, David John, et al. “Storm-Based Probabilistic Hail Forecasting with Machine Learning Applied to Convection-Allowing Ensembles.” Weather and Forecasting, vol. 32, no. 5, 22 Sept. 2017, pp. 1819–1840, https://doi.org/10.1175/waf-d-17-0010.1. 

# Requirements Document
