# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImageMap</title>
</head>
<style>
    *{margin: 0;}
</style>
<script>
    function coordinate(event)
    {
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("Text1").value=x;
        document.getElementById("Text2").value=y;
    }
</script>
<body>
    <IMG src="![WhatsApp Image 2024-04-16 at 19 07 46_58adc043](https://github.com/vijayr21/NearMe/assets/149347607/e21a036a-b73b-4526-8b21-3a284108f539)
" width="1535" height="650" usemap="#MapNew" onmousemove="coordinate(event)">
        <MAP name="MapNew">
            <AREA shape="rect" coords="160,359,376,443" href="https://www.makemytrip.com/hotels/hotel-listing/?topHtlId=201712071752368734&city=CTMAA&country=IN&checkin=04132024&checkout=04142024&roomStayQualifier=2e0e&totalGuestCount=2&roomCount=1&cmp=googlehoteldfinder_DH_META_Paid_selected_IN_mapresults_201712071752368734&_uCurrency=INR&Campaign=20613919640&locusId=CTMAA&locusType=city&mtkeys=b1e79af8-c554-48b3-a52c-85fea70907c2&au=&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5iBWH_sKzcQ-sYrPVV0CsKUtGbCrrPjzCzd6cFU2R0VyBaiO8_RWIQaAlTaEALw_wcB" title="Moon view beach resort">
                <AREA shape="rect" coords="406,278,536,332" href="https://www.agoda.com/search?campaignid=21176660567&searchdatetype=selected&lt=1&numberofchildren=0&childages=&gsite=mapresults&partnercurrency=INR&roomid=655899473&pricetax=330.62&pricetotal=3085.76&rateplan=937fa546-fec5-fcbc-2b5d-04f22c071a13&usercountry=IN&currency=INR&userdevice=desktop&verif=false&audience_list=&mcid=332&booking_source=cpc&adtype=1&push_id=CgYIgJbnsAYSBgiAueywBhgBIKDy7xIqDBgBKggiAggBKgIIBA%3D%3D937fa546-fec5-fcbc-2b5d-04f22c071a13_20240412_10&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5g7RTaTN6JjXjGwhXTSIBNj2jEWvioBiR5E6ERoIoKHIBOLpYgYDhwaAkeBEALw_wcB&los=1&adults=2&rooms=1&checkin=2024-04-13&checkout=2024-04-14&selectedproperty=39581984&city=17269&cid=1918349&pslc=1&ds=IUpATh8VkRCiNnAT" title="Laksh Grand Resort">
                    <AREA shape="rect" coords="539,345,667,407" href="https://www.goibibo.com/hotels/meta/google/4354390963378411938/3540257811845764463/%7B%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22ibp%22:%22v15%22%7D/?hquery={%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22qd%22:%2220240413-20240414-1-2_0%22,%22ibp%22:%22v15%22}&utm_source=meta&cmp=META|google|cpc_hpa|googlehoteldfinder|Hotel_Price_Ads_3540257811845764463|META&utm_medium=cpc_hpa&utm_campaign=Hotel_Price_Ads_19905350044_3540257811845764463&vendor=gds&p=1636.40&c=INR&bookingSource=commissions&adType=1&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5iq5W5ntjSqfMfzNq0F0wSaCOn3dwkJw3Tig3aqE1EUBWPbvzKjAhcaArdQEALw_wcB" title="Country club Lee Crysstal - Boutique Hotel">
                        <AREA shape="rect" coords="742,162,919,218" href="https://www.makemytrip.com/hotels/hotel-listing/?topHtlId=202109211631562045&city=CTMAA&country=IN&checkin=04132024&checkout=04142024&roomStayQualifier=2e0e&totalGuestCount=2&roomCount=1&cmp=googlehoteldfinder_DH_META_Paid_selected_IN_mapresults_202109211631562045&_uCurrency=INR&Campaign=20607960138&locusId=CTMAA&locusType=city&mtkeys=3ea0338e-cf36-453a-bc7c-c382698d6ca7&au=&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5gWDllpXvek6_tZCDcm1sRYgZE-3w3I1jYg2b3tZrbNOFVXFiORQK4aAhM3EALw_wcB" title="Le Grace chennai ECR">
                            <AREA shape="rect" coords="1102,397,1302,447" href="https://www.goibibo.com/hotels/meta/google/4354390963378411938/9148435948091139586/%7B%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22ibp%22:%22%22%7D/?hquery={%22ci%22:%2220240413%22,%22co%22:%2220240414%22,%22r%22:%221-2_0%22,%22qd%22:%2220240413-20240414-1-2_0%22,%22ibp%22:%22%22}&utm_source=meta&cmp=META|google|cpc_hpa|googlehoteldfinder|Hotel_Price_Ads_9148435948091139586|META&utm_medium=cpc_hpa&utm_campaign=Hotel_Price_Ads_19905408880_9148435948091139586&vendor=&p=21186.90&c=INR&bookingSource=commissions&adType=1&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5iVKB2gnAmkqssixOUUTLRI5VUHnbzeIEoIB9OKpfHmnlCtRsgHHs4aApKbEALw_wcB" title="Mer Vue Villa (Beach house)">
                                <AREA shape="rect" coords="1076,69,1220,112" href="https://www.agoda.com/search?campaignid=21176660567&searchdatetype=selected&lt=1&numberofchildren=0&childages=&gsite=mapresults&partnercurrency=INR&roomid=565105220&pricetax=183.60&pricetotal=1713.60&rateplan=85baaefd-ec1c-e203-6ca2-f8eb2c1cb9fb&usercountry=IN&currency=INR&userdevice=desktop&verif=false&audience_list=&mcid=332&booking_source=cpc&adtype=1&push_id=CgYIgJbnsAYSBgiAueywBhgBINymhAEqDBgBKggiAggBKgIIBA%3D%3D85baaefd-ec1c-e203-6ca2-f8eb2c1cb9fb_20240412_10&gclid=Cj0KCQjwlN6wBhCcARIsAKZvD5g9nlLSTab6PdGHzDlDE_O3sPX4chFt2OcJ6MSwmuQdiKuXjwJ9wcwaAkkYEALw_wcB&los=1&adults=2&rooms=1&checkin=2024-04-13&checkout=2024-04-14&selectedproperty=2167644&city=17269&cid=1918349&pslc=1&ds=lMZDA4D1wPuieZNR" title="Grand Bay resort">
        </MAP>
        <br>
        X-coordinate
            <input type="text" id="Text1">
        Y-coordinate 
            <input type="text" id="Text2">
</body>
</html>
```


## OUTPUT
![Screenshot 2024-04-16 185943](https://github.com/vijayr21/NearMe/assets/149347607/8fc5a0f6-e57d-4eaa-b83a-cbab13fe98f0)
![Screenshot 2024-04-16 190002](https://github.com/vijayr21/NearMe/assets/149347607/1d64e53c-3343-4535-8a25-69365b5a55ca)
![Screenshot 2024-04-16 190012](https://github.com/vijayr21/NearMe/assets/149347607/e8fd5925-a446-4b68-9b97-8e7cffd940d7)
![Screenshot 2024-04-16 190020](https://github.com/vijayr21/NearMe/assets/149347607/a3feadfd-dfc1-4137-9c5e-7f0dee76e8b7)
![Screenshot 2024-04-16 190027](https://github.com/vijayr21/NearMe/assets/149347607/596e7c62-b92b-4561-abe0-09a1bc281238)
![Screenshot 2024-04-16 190034](https://github.com/vijayr21/NearMe/assets/149347607/a29ffba3-724f-45a8-9db1-ce142a45dda3)
![Screenshot 2024-04-16 190040](https://github.com/vijayr21/NearMe/assets/149347607/fc1c77f7-9c40-48bb-bbb8-414e6ba788e9)
![Screenshot 2024-04-16 190048](https://github.com/vijayr21/NearMe/assets/149347607/616d592b-aba6-4c78-9776-aba0722ea3a9)
![Screenshot 2024-04-16 190054](https://github.com/vijayr21/NearMe/assets/149347607/c6359d97-e4f8-4797-bdf6-96f30493c706)
![Screenshot 2024-04-16 190101](https://github.com/vijayr21/NearMe/assets/149347607/c787b658-9d2f-4f11-98ad-0e8a9d345d6d)
![Screenshot 2024-04-16 190106](https://github.com/vijayr21/NearMe/assets/149347607/6aca0068-a34e-44b9-a470-409e36d80a6a)
![Screenshot 2024-04-16 190114](https://github.com/vijayr21/NearMe/assets/149347607/67df143e-0d93-4e38-96fd-c6aa7e8c2a7e)


## RESULT
The program for implementing image maps using HTML is executed successfully.
