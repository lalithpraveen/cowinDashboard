**Straw-Hat**
**Live link** https://strawhatcowin.ccbp.tech/ 

In this project,  built a **CoWIN Dashboard** by applying the concepts I have learned till now.

### Refer to the images below:

**Success View** <br/>

<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/cowin-dashbaord-output.gif" alt="cowin-dashboard-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

**Failure View** <br/>

<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/cowin-dashbaord-failure-view-output.gif" alt="cowin-dashboard-failure-view-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>


### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>



<details>
<summary>Functionality to be added</summary>
<br/>

The app have the following functionalities

- When the page is opened,
  - An HTTP GET request be made to the **covidVaccinationDataApiUrl**
  - **_loader_** should be displayed while the HTTP request is fetching the data
  - After the HTTP request is successful, the response received should be displayed using different charts from `recharts`
  - The last 7 days vaccination data should be displayed using the `BarChart` component from `recharts`
  - The data for vaccination by gender and vaccination by age should be displayed as two different pie charts using the `PieChart` component from `recharts`
  - When the HTTP GET request to the **covidVaccinationDataApiUrl** returns an error response then the [FailureView](https://assets.ccbp.in/frontend/react-js/api-failure-view.png) should be displayed
  </details>

<details>

- **covidVaccinationDataApiUrl** : https://apis.ccbp.in/covid-vaccination-data

</details>

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/api-failure-view.png](https://assets.ccbp.in/frontend/react-js/api-failure-view.png) 
- [https://assets.ccbp.in/frontend/react-js/cowin-logo.png](https://assets.ccbp.in/frontend/react-js/cowin-logo.png)
</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #161625; width: 150px; padding: 10px; color: white">Hex: #161625</div>
<div style="background-color: #2cc6c6; width: 150px; padding: 10px; color: black">Hex: #2cc6c6</div>
<div style="background-color: #cbd5e1; width: 150px; padding: 10px; color: black">Hex: #cbd5e1</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #1c1c2b; width: 150px; padding: 10px; color: white">Hex: #1c1c2b</div>
<div style="background-color: #2d87bb; width: 150px; padding: 10px; color: black">Hex: #2d87bb</div>
<div style="background-color: #a3df9f; width: 150px; padding: 10px; color: black">Hex: #a3df9f</div>
<div style="background-color: #64c2a6; width: 150px; padding: 10px; color: black">Hex: #64c2a6</div>
<div style="background-color: #94a3b8; width: 150px; padding: 10px; color: black">Hex: #94a3b8</div>
<div style="background-color: #f54394; width: 150px; padding: 10px; color: black">Hex: #f54394</div>
<div style="background-color: #5a8dee; width: 150px; padding: 10px; color: black">Hex: #5a8dee</div>
<div style="background-color: #2cc6c6; width: 150px; padding: 10px; color: black">Hex: #2cc6c6</div>
<div style="background-color: #6c757d; width: 150px; padding: 10px; color: black">Hex: #6c757d</div>
<div style="background-color: #5a8dee; width: 150px; padding: 10px; color: black">Hex: #5a8dee</div>

</details>


