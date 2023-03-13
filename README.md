# Demo-Jupyter-Notebook-with-CCS-Data
Demo of jupyter notebook in ArcGIS Pro environment using UDOT Continuous Count Station data

Instructions:
1. Download (or clone) respository
2. Unzip the processed (parsed from pdfs and excel files) CCS data file: data\CCSHourDir_2013to2019.zip
3. Open 'Demo-Notebook.ipynb' in Jupyter using ArcGIS Pro environment ([more info](https://developers.arcgis.com/python/guide/using-the-jupyter-notebook-environment/))
    1. From Start Menu, go to ArcGIS group and select 'Python Command Prompt.' (Note: This will load command prompt in ArcGIS Pro's active python environment)
    2. Use DOS commands to navigate to directory with downloaded repository. You must be in the downloaded folder or above it to be able to access it through jupyter notebook.
    3. Type 'jupyter notebook' and press Enter. This will open your default web browser to the jupyter notebook interface.
    4. Navigate to the folder where you downloaded or cloned repository.
    5. Open 'Demo-Notebook.ipynb' by clicking on the file.
4. Execute cells one-by-one by pressing SHIFT+ENTER to excute cell and move to the next one. (CTRL+ENTER will execute current cell without moving to next.)

If you want to see the 2019 data in its original pre-processed glory, visit the data\\_udot-ccs-data-2019-original\ folder.

Additional Resources:
1. [Visualizing Data with the Spatially Enabled DataFrame](https://developers.arcgis.com/python/guide/visualizing-data-with-the-spatially-enabled-dataframe/)
2. [Data Engineering with Spatially Enabled DataFrames and ArcGIS API for Python](https://www.youtube.com/watch?v=24KZCkApGmA)
3. [Jupyter/IPython Notebook Quick Start Guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)
3. [How to Use Jupyter Notebook: A Beginner’s Tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)
4. UDOT Learning Portal Course: [Beginning Data Science with Python and Jupyter](https://utah-udotu_public.sabacloud.com/Saba/Web_spf/NA1PRD0101/common/ledetail/cours000000000026969)
