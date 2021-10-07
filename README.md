# SpringWorksHA

1. Requirements from [Springworks](https://github.com/Springworks/recruitment-waypoints-challenge). 

2. Implementation
- Load JSON file to a table and show it on a web page. 
    - Press button to show the driving log.
    - Load waypoints data into table content.
    - Convert timestamp to human-friendly format.
    - Add index row for table. 
    - Style the table and button. 
- Categorise driving records and generate a driving report. 
    - Press button to show the report. 
    - Calcutate the distance of two waypoints based on coordinate of latitude and longitude. 
    - Read time into constant, calcutate the interval between each waypont. 
    - Calculate speed by distance/time-interval and compare with speed limit, categories the result. 
    - Generate final report, show how well the user (Peter Griffin) stick to the speed limits while driving. 
- Test. 

3. Running this program locally 
- 
    ```
    npm install
    npm start
    ``` 
- Or view index.html with [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) if you use VS Code.  

4. Potential features.
- Integrate with google map API, show driving history on the map. 
- Calculate score based on the driver's ability to drive safely, eg. how close to the speed limit, how often he drives over the speed limit. 
- Generate driving report in csv or other format. 

5. Reference
- [Convert JSON to Table](https://www.encodedna.com/javascript/practice-ground/default.htm?pg=convert_json_to_table_javascript).
- [Calculate distance based on latitude and longitude](https://www.geodatasource.com/developers/javascript).
- [Button Style](https://getcssscan.com/css-buttons-examples).