# vehicle_traffic_in_Norway
A study of vehicle traffic in Norway based on data obtained via an API of The Norwegian Public Roads Administration

Files and folders:

1. traffic_analysis.ipynb - Jupyter notebook with all Python codes (basically one may copy only this file)
2. ./figures - self-explainatory
3. ./maps_for_kepler.gl - folder with two maps for kepler.gl (*.json) and examples (*.png):
    - TRP_map.json - map of TRPs (Traffic Registration Points) in Norway
    - YoY_traffic_comparison_map.json - maps with YoY comparison of vechichle traffic in Norway (2020.07.27 to 2019.07.27)
    Notes on use of Kepler.GL (very easy):
          1. go to Kepler.GL
          2. press "GET STARTED"
          3. drag and drop a json

4.   *.pkl - pickle files with data and results (2020.07.27). 
     It is not obligatory to copy them. But if they are missed or deleted, at launch of the notebook the traffic data will be requested/processed anew (it takes ca. hour).
      "TDD_Randaberg.pkl" - traffic data for TRPs in Randaberg kommune
      "TDD_ALL.pkl" - traffic data for all TRPs in Norway
      "norway_vehicles.pkl" - processing results
      "norway_bicycles.pkl" - processing results

5.  *.logs - log files of traffic data requests

6. *.csv:
    TRP.csv - a csv file with coordinates of TRPs in Norway. May be visualized by Kepler.GL
    
    TRP_YoY.csv - a csv file with coordinates of TRPs in Norway. May be visualized by Kepler.GL
