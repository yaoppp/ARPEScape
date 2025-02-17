## Log of updates to ARPEScape
**ARPEScape-v8.0.0 - 21.07.2023:**  
-> Schism of codebase:  
--> PESTools: All ADRESSTools associated with ARPES and PES data processing and analysis is now an independent software packaged called ARPEScape, available here 'https://github.com/c0deta1ker/ARPEScape'.  
--> Materials Properties Database: Now an independent software package called MatBase, available here 'https://github.com/c0deta1ker/MatBase'.  
--> Went through and fixed many bugs and made some updates to the codebase to make it run better.

**Eos - 10.06.2023:**   
-> New Database available: Crystallography database  
--> Added new function that extracts crystal properties and Brilluoin zone.  
--> Extract Brilluoin Zone slice function, with the possibility to rotate and translate the origin for aligning Fermi Surface scans with ARPES.  
-> New App available: Crystallography plotter.   
-> New App available: Main Menu app allowing the user to navigate to all otehr apps using this single app.  
-> Updated all other Apps to make them faster to run.  

**Eos - 10.04.2023:**   
-> The Material Database is now an independent package that does not depend on the PESTools package.  
-> New App available: IMFP determination via an app using 'IMFP_UI'.  
-> New App available: PES binding energy spectrum, photoionisation cross-section and asymmetry app using 'PES_UI'.  
-> Updated PEARL data-loader function.  

**Dionysus - 22.10.2022:**   
-> Multiple bug fixes and improvement of PES / XPS analysis and curve fitting tools.  
-> Improvement to figure aesthetics used in the codebase.  
-> Updated GitHub Repo information and added several showcases of the functions available in ADRESSTools.  
-> More generalised EF fitting function, allowing more accurate fits to the EF edge.  
-> Updated angle -> wave-vector conversions to take into account new ADRESS geometry.  

**Cronus - 28.09.2022:**   
-> Multiple bug fixes and improvement of PES / XPS analysis and curve fitting tools.  
-> Updated Theory Data from Microsoft - all up-to-date now.  
-> Added Physics Constants to Materials Database.  
-> Uploaded MATools to 'Skyfall' version, with new ARPES geometry considered.  

**Basil - 21.02.2022:**   
-> Multiple bug fixes and improvement of PES / XPS analysis and curve fitting tools.  

**Ajax - 24.11.2021:** Integration of PES / XPS analysis and curve fitting tools.  

**v2.1 - 17.07.2020:** Massive upgrade to all UI systems and added several new features for analysis.  

**v2.0 - 13.11.2019:** Further development of all UI's to make them all consistent;  
-> When saving on the 'arpes_processor' UI, it will now automatically also save an info .txt file.  
-> Added new method in 'kf_analysis' that will track states by measuring the full-width at half-maximum as a function of a scan parameter. This method allowed for kF to be tracked automatically using the algorithm, with the user only defining the region of interest.  
-> Added feature in 'kf_analysis' that will plot a summary video showing the fits as a function of the scan parameter.  
-> Merging to master.

**v1.8 - 06.02.2019:** Further development of the 'arpes_statefitting' UI;  
	-> Added Voigt curve that can be fitted.  

**v1.7 - 18.12.2018:** Further development of the 'arpes_statefitting' UI;  
	-> Combined fit range and fit routine functions.  

**v1.6 - 06.12.2018:** Developed all UI's to be mutually consistent in forms.  

**v1.5 - 28.11.2018:** Developed the 'kf_analysis' UI.  

**v1.4 - 26.11.2018:** Developed the 'bz_navigation' UI.  

**v1.3 - 24.11.2018:** Developed the 'arpes_isoeanalysis' UI.  

**v1.2 - 10.11.2018:** Developed the 'arpes_statefitting' UI.  

**v1.1 - 05.11.2018:** Developed the 'arpes_processor' UI.  

**v1.0 - 10.10.2018:** Single GUI to perform all processing and analysis.  

## List of known bugs
