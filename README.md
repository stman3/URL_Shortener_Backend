URL_Shortener_Backend
_______________________________
To test the backend send request
http://localhost:5000/api/url/shorten



Example
Send post request To http://localhost:5000/api/url/shorten

The body:

JSON
{
    "longUrl": "https://www.amazon.com/UMREN-Evening-Rhinestones-Wedding-Handbag/dp/B07Y62NHJW/ref=lp_23763059011_1_2"
}
The response we will be like This 

{
    "urlCode": "dN_SNUD0R",
    "longUrl": "https://www.amazon.com/UMREN-Evening-Rhinestones-Wedding-Handbag/dp/B07Y62NHJW/ref=lp_23763059011_1_2",
    "shortUrl": "http://localhost:5000/dN_SNUD0R",
    "date": "Fri Apr 08 2022 01:12:54 GMT+0300 (Arabian Standard Time)",
    "_id": "624f61e6f1a4ed01cef0791f",
    "__v": 0
}

Go To The shortUrl and it will redirect to the orginal URL
_______________________________
The Server running on port 5000
