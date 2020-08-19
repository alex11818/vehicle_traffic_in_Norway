# vehicle_traffic_in_Norway
A study of vehicle traffic in Norway based on data obtained via API of The Norwegian Public Roads Administration

Files and folders:

1. traffic_analysis.ipynb - Jupyter notebook with all Python codes (basically one may copy only this file). 
   
   NB! Some sections (section "Polling all TRPs in Norway" runs ca. one hour) take a long time to run
   
2. ./figures - it is where all the figures are saved
3. ./maps_for_kepler.gl - folder with two maps for kepler.gl (*.json) and examples (*.png):
    - TRP_map.json - map of TRPs (Traffic Registration Points) in Norway
    - YoY_traffic_comparison_map.json - maps with YoY comparison of vechichle traffic in Norway (2020.07.27 to 2019.07.27)
    
    Notes on use of Kepler.GL (very easy):
    1. go to Kepler.GL
    2. press "GET STARTED"
    3. drag and drop a json

4. *.csv:
    - TRP.csv - a csv file with coordinates of TRPs in Norway. May be visualized by Kepler.GL
    - TRP_YoY.csv - a csv file with coordinates of TRPs in Norway. May be visualized by Kepler.GL

5.   *.pkl - pickle files with data and results (2020.07.27). 
     Unfortunately, it is not possible to upload the datasets listed below due to github restrictions (they are > 25 MB)
     It is not obligatory to copy them, as they will be created during the notebook run.
     However, it may take some time: section "Polling all TRPs in Norway" takes ca. hour run.
      - "TDD_Randaberg.pkl" - traffic data for TRPs in Randaberg kommune
      - "TDD_ALL.pkl" - traffic data for all TRPs in Norway
      - "norway_vehicles.pkl" - processing results
      - "norway_bicycles.pkl" - processing results

6. requirements.txt - list of the required packages.
   the packages can be installed (in JupyterLab) by: 
   !pip install -r requirements.txt 
