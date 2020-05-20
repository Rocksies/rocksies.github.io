![alt text](https://github.com/Rocksies/rocksies.github.io/blob/soil-profile/Logo.JPG)

# SSP Geotechnics - Rocksies 

**About:**
<br>
Reimagining geological data and enabling accessibility for the future. 
<br>

**Aims:** 
<br>
1. Creating a space to collate available geotechnical data in Malaysia from SSP S/B. 
2. Having an interactive mapping GUI that can be navigated and searched with geolocation. 
3. Connect available ground profiles via SQL database with a cloud back-end service for constant availability and high reliability. 

<br> 
Last updated: 15th May 2020 
<br> 

const client = new Client({});

client
  .elevation({
    params: {
      locations: [{ lat: 45, lng: -110 }],
      key: process.env.GOOGLE_MAPS_API_KEY
    },
    timeout: 1000 // milliseconds
  }, axiosInstance)
  .then(r => {
    console.log(r.data.results[0].elevation);
  })
  .catch(e => {
    console.log(e);
  });
  
