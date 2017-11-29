#Overview
The intent of this assignment is gauge your general level of coding proficiency as well as your ability to think through the design of a web application. 

Feel free to make assumptions regarding anything that isn’t clear. This exercise doesn’t have a single right answer. The important part is to be able to explain the rationale behind your decisions. Also, the intent behind the assignment is not to make you design and implement every single detail and corner case but rather to help us understand your level of comprehension and your thought process when making design choices. The assignment shouldn’t take you more than a few hours.

Provide documentation for the assignment as necessary, and be prepared to walk us through your application during your interview.

#Requirements
Design and implement a web application that collects local weather data from a simulated IoT device via a REST API. The web application should save the data in a database and display it in an interactive visualization. Assume the IoT device reports the device ID, timestamp, temperature, and humidity. Assume new data is available every 60 seconds.

The following is an example data set from the IoT device:

| Device ID | Timestamp             | Temperature (F) | Humidity (%) |
|-----------|-----------------------|:---------------:|--------------|
| 1234ABCD  | 12 July 2017 08:13:00 |            75.0 |           37 |
| 1234ABCD  | 12 July 2017 08:14:00 |            75.1 |           39 |
| 1234ABCD  | 12 July 2017 08:15:00 |            75.5 |           40 |
| 1234ABCD  | 12 July 2017 08:16:00 |            75.3 |           45 |
| 1234ABCD  | 12 July 2017 08:17:00 |            75.2 |           41 |
| 1234ABCD  | 12 July 2017 08:18:00 |            74.8 |           38 |
| 1234ABCD  | 12 July 2017 08:19:00 |            74.3 |           39 |
| 1234ABCD  | 12 July 2017 08:20:00 |            74.6 |           41 |
| 1234ABCD  | 12 July 2017 08:21:00 |            74.9 |           35 |
| 1234ABCD  | 12 July 2017 08:22:00 |            75.0 |           30 |