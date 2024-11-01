
[<img src="https://about.mappls.com/about/images/MAPPLS-MapmyIndia-logo.png" height="40"/> </p>](https://about.mappls.com/api/)


# Routing API
<!--<div style="display: flex; justify-content: space-between;">
  <span>Version: 1.0</span>
  <span>Author: Ritesh Arora</span>
</div>-->

```Version:1.0                                                              Author: Ritesh Arora```

> **URL:**  https://intouch.mapmyindia.com/iot/api/route/ 

# Authorization:

 This API follows OAuth2 based security. To know more on how to create your authorization tokens, please use our authorization token URL. More details available [here](https://www.mapmyindia.com/api/advanced-maps/doc/authentication-api.php).

**The API leverages OAuth 2.0 based security. Hence, the developer would need to send a request for access token using their client_id and client_secret to the OAuth API. Once validated from the OAuth API, the access_token and the token_type need to be sent as Authorization header with the value: `"{token_type} {access_token}”`.
Authorization: `token_typeaccess_token.`**

## HTTP Method: 
GET


### **Request Parameters:**


| **Parameter Name** | **Data Type** | **Description** |
| --- | --- | --- |
| accountId | Long | Account ID for which the routes need to be fetched. |
| id | Long | Route IDs |

<br></br>

### **Sample curl Request:**

```JSON
    {
        "id": 624737,
        "name": "AL (JBS-RGIA)",
        "createdOn": 1651490995,
        "updatedOn": 1667558807,
        "type": 2,
        "routeType": 1,
        "geofenceId": [
            786511,
            680515,
            680516,
            680517,
            680518,
            680519,
            680520,
            680521,
            680522,
            786475,
            680524,
            680525,
            680526,
            680527,
            680529,
            680530
        ]
    }
```

### **Response:**

| **HTTP Status Code** | **Reason** | **Response Model** |
| --- | --- | --- |
| 200 | Ok | Refer above sample curl |
| 400 | Bad Request |  |
| 401 | Unauthorized |  |
| 403 | Forbidden |  |
| 404 | Not Found |  |
| 500 | Internal Server Error |  |

<br></br>

## **Route Creation API**

### ***Input URL***

https://intouch.mapmyindia.com/iot/api/route/?name=new%20delhi&geofenceId=677042,677043,680516&routeType=1

---
## **HTTP Method:**
 *POST*


### **Request Parameters:**

| **Parameter Name** | **Data Type** | **Description** |
| --- | --- | --- |
| name | String | Name of the Route to be created. |
| geofenceId/{latitude},{longitude} | Array (Long) | Geofence IDs to be included as touch points in between the route. |
| routeType | String | 1- normal 2 - short (optimized) |


## **Sample curl Request:**

<br>

```Json
{
    "id": 831549
}
```




<br></br>

For any queries and support, please contact: 

[<img src="https://about.mappls.com/images/mappls-logo.svg" height="40"/> </p>](https://about.mappls.com/api/)
Email us at [apisupport@mappls.com](mailto:apisupport@mappls.com)


![](https://www.mapmyindia.com/api/img/icons/support.png)
[Support](https://about.mappls.com/contact/)
Need support? contact us!

<br></br>
<br></br>

[<p align="center"> <img src="https://www.mapmyindia.com/api/img/icons/stack-overflow.png"/> ](https://stackoverflow.com/questions/tagged/mappls-api)[![](https://www.mapmyindia.com/api/img/icons/blog.png)](https://about.mappls.com/blog/)[![](https://www.mapmyindia.com/api/img/icons/gethub.png)](https://github.com/Mappls-api)[<img src="https://mmi-api-team.s3.ap-south-1.amazonaws.com/API-Team/npm-logo.one-third%5B1%5D.png" height="40"/> </p>](https://www.npmjs.com/org/mapmyindia) 



[<p align="center"> <img src="https://www.mapmyindia.com/june-newsletter/icon4.png"/> ](https://www.facebook.com/Mapplsofficial)[![](https://www.mapmyindia.com/june-newsletter/icon2.png)](https://twitter.com/mappls)[![](https://www.mapmyindia.com/newsletter/2017/aug/llinkedin.png)](https://www.linkedin.com/company/mappls/)[![](https://www.mapmyindia.com/june-newsletter/icon3.png)](https://www.youtube.com/channel/UCAWvWsh-dZLLeUU7_J9HiOA)




<div align="center">@ Copyright 2022 CE Info Systems Ltd. All Rights Reserved.</div>

<div align="center"> <a href="https://about.mappls.com/api/terms-&-conditions">Terms & Conditions</a> | <a href="https://about.mappls.com/about/privacy-policy">Privacy Policy</a> | <a href="https://about.mappls.com/pdf/mapmyIndia-sustainability-policy-healt-labour-rules-supplir-sustainability.pdf">Supplier Sustainability Policy</a> | <a href="https://about.mappls.com/pdf/Health-Safety-Management.pdf">Health & Safety Policy</a> | <a href="https://about.mappls.com/pdf/Environment-Sustainability-Policy-CSR-Report.pdf">Environmental Policy & CSR Report</a>

<div align="center">Customer Care: +91-9999333223</div>









