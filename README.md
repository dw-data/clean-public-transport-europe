# clean-public-transport-europe
We collected data in three areas:
1. Transport
2. Pledges
3. Pollution

#### 2. Pledges
From the pledges we identified, we selected those concerning "buses", "all transport", and "ferries". Since our analysis focused solely on assessing ambition and commitment toward net-zero emissions, we excluded pledges on "metro" and "tram," as these modes of transport do not produce direct GHG emissions.

While reviewing, we ensured no duplicates were taken in account. Pledges too vague (eg. lacking a target and/or goal year) were excluded. 

We scored pledges aiming for net-zero emissions according to the following table:
<table>
  <tr>
    <td>Until 2025</td>
    <td>3.5 points</td>
  </tr>
  <tr>
    <td>2026-2030</td>
    <td>3</td>
  </tr>
  <tr>
    <td>2031-2035</td>
    <td>2.5</td>
  </tr>
  <tr>
    <td>2036-2040</td>
    <td>2</td>
  </tr>
  <tr>
    <td>2041-2045</td>
    <td>1.5</td>
  </tr>
  <tr>
    <td>2046-2050+</td>
    <td>1</td>
  </tr>
  <tr>
    <td>100% net-zero or no diesel fuels</td>
    <td>1</td>
  </tr>
  <tr>
    <td>100% electric</td>
    <td>2</td>
  </tr>
  <tr>
    <td>increase of vehicles</td>
    <td>0.5</td>
  </tr>
  <tr>
    <td>pledged but status not completed or unknown in target year</td>
    <td>-0.5</td>
  </tr>
  <tr>
    <td>new vehicles only</td>
    <td>-0.1</td>
  </tr>
</table> 


### Definitions
We have not included door-to-door or special-purpose vehicles since these were not homogeneously categories reported across the board. 

Electric buses include: battery electric buses, fuel cell buses, untracapacitor buses and electric trolley buses.

"Other transport" includes funiculars (eg. Zagreb), ferries (eg. Amsterdam)

Cities where the county, province and/or immediate surroundings have been considered (buses):
- Antwerp
- Bucharest
- Paris
- Stockholm
- Zagreb

### Sources

CDP Full Cities Public Data Separated by Question datasets. CDP is a global non-profit running an environmental reporting system for cities and companies. These datasets are collected in partnership by CDP and ICLEI - Local Governments for Sustainability.

We retrieved data in our three target areas for 20xx to 2025 found under the following questions:
- "Report the total emissions, fleet size and number of vehicle types for the following modes of transport"
- "Provide details of your jurisdiction's energy-related and other environment-related targets active in the reporting year."

2025 and 2024 datasets were not acce

Although most transport data were formally structured, the qualitative aspect of pledges data along with the frequent changes in question names and numbers, city identifiers and cities included, and the rich information embedded in the comment fields led us to opt for manual data collection in these two questions. 

For the years 20xx to 2018, we ran data queries on CDP's browser, filtered by:
- CDP Region: Europe
- Question Name: Please provide the total fleet size and number of vehicle types
- Column Name: Number of Buses
