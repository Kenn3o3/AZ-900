# [[Global Infrastructure]]
## Paired Regions

<hr>

-   Each region is paired with another region 300 miles away.
-   Only one region is updated at a time to ensure no outages
	-   Some Azure Services rely on Paired Regions for ==Disaster Recovery==

E.g. Azure Geo-redundant Storage (GRS) replicates data to a secondary region automatically , ensuring that data is durable even in the event that the primary region isn’t recoverable.

<table border = "1">  
  <tr>  
    <td>Canada</td>  
    <td>Canada Central</td>
    <td>Canada East</td>  
  </tr>  
  <tr>  
    <td>North America</td>  
    <td>East US</td>  
    <td>West US</td>
  </tr>  
  <tr>  
    <td>Germany</td>  
    <td>Germany Central</td>  
    <td>Germany Northwest</td>
  </tr>  
</table>

<hr>



-> [[Region Types and Service Availability]]

<- [[Regions and Geographies]]

<- [[Main]]