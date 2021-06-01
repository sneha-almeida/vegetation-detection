# Calculation of Vegetation Cover From Maps Downloaded in Real Time

The system works in following steps:
1) User enters the email ID and the location(country or city) that they want the percetage vegetation for 
2) The system downloads the map of the region entered by the user
3) Then the system uses techniques like colour band detection, finding specific coloured contours and calculating the area of the contours of interest
4) The ratio of area of those contours as against the total area give the percetange of the area under vegetation
5) Then the following details are curated in a PDF in real time:
  a) Logo 
  b) Name of the region 
  c) Map of the region 
  d) Area under vegetation depeicted using a Pie Chart
6) An email sent with the PDF as attachment to the user(on the email ID mentioned in step 1) 

The generated PDF is here 
https://github.com/sneha-almeida/vegetation-detection/blob/main/1_updated_details.pdf. 
