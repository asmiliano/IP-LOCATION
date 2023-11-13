## The "IP-INFO" script is a Python tool designed for retrieving detailed information about a specified IP address using the ip-api.com JSON API. 

The script utilizes the `requests` library to make API requests, processes the 
JSON response to extract relevant details (such as ISP, organization, country, region, and city), 
and displays the information in a structured format. Additionally, it generates an interactive 
map using the `folium` library, centered at the IP address's geographical coordinates, and saves the map as an HTML file. 
The script provides a user-friendly interface, prompting the user to input a target IP address.
Exception handling is implemented to address potential connection issues. 
This tool can be useful for obtaining quick insights into the geographic and network-related details of a given IP address.
