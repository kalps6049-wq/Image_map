# Ex04 Places Around Me
# Date:05.10.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
    <head >
        <title>
            Image Map
        </title>
        
        
    </head>
    <body>
        <h1 align = center>
        <font color="orange"><b>MADURAI</b></font>
        </h1>
        <h3 align = center>
        <font color="blue"><b>KALPANA M (25014380)</b>
        </h3>
        <center>
        <img src="map.png" usemap="My Hometown" height="610" weight="1450">
        <map name="My Hometown">
            <area shape="poly" coords="677,215,789,218,791,318,672,316"  title="temple" href="temple.html">
            <area shape="poly" coords="870,401,972,405,986,488,848,486" title="mahal" href="mahal.html">
            <area shape="poly" coords="456,426,584,426,595,494,472,504" title="azagar" href="azagar.html">
            <area shape="poly" coords="364,167,504,164,511,235,383,242" title="hotel" href="hotel.html">
            <area shape="poly" coords="878,291,1021,287,1018,354,890,358" title="jigar" href="jigar.html">
        </map>
        </center>
    </body>
</html>

temple.html

<html>
    <head>
        <title>temple</title>
    </head>
        <body bgcolor="beige">
            <h1 align="center">
                <font color="pink"><b>MADURAI</b></font>
            </h1>
            <h3 align="center">
                <font color="purple"><b>MEENAKSHI AMMAN TEMPLE</b></font>
            </h3>
            <hr size="3" color="pink">
            <center>
            <img src="meenakshi.png" height="600" width="600">
            </center>
            <p align="justify">
                <font face="TEMPLE" size="6">
                    The Meenakshi Amman Temple in Madurai is one of the most magnificent and spiritually significant temples in India,
                     renowned for its architectural brilliance, deep-rooted mythology, and cultural vibrancy. Dedicated to Goddess
                      Meenakshi, a form of Parvati, and her consort Sundareswarar, a form of Lord Shiva, the temple stands as a symbol
                       of divine union and feminine power. Unlike many other temples where the male deity is central, this temple uniquely
                        honors the goddess as the primary deity, reflecting the matrilineal traditions and rich heritage of Tamil culture. 
                        Spanning over 14 acres in the heart of the ancient city of Madurai, the temple complex is a marvel of Dravidian architecture,
                         with its towering gopurams (gateway towers) adorned with thousands of colorful, intricately sculpted statues depicting gods,
                          goddesses, demons, and celestial beings from Hindu mythology. The tallest of these towers reaches nearly 170 feet, drawing the 
                          eyes of visitors from miles away. Inside the temple, the famed Hall of a Thousand Pillars (Aayiram Kaal Mandapam) showcases stunning
                           craftsmanship, each pillar uniquely carved with mythical creatures and scenes.
                </font>
            </p>
            

        </body>
 </html>

 mahal.html

 <html>
    <head>
        <title>temple</title>
    </head>
        <body bgcolor="beige">
            <h1 align="center">
                <font color="pink"><b>MADURAI</b></font>
            </h1>
            <h3 align="center">
                <font color="purple"><b>THIRUMALAI NAYAKAR MAHAL</b></font>
            </h3>
            <hr size="3" color="pink">
            <center>
            <img src="mahal.png" height="600" width="600">
            </center>
            <p align="justify">
                <font face="TEMPLE" size="6">
                    Thirumalai Nayakar Mahal, located in the heart of Madurai, is a magnificent palace built in 1636 AD by King Thirumalai Nayak of the Nayak dynasty,
                     who ruled the region between 1623 and 1659. Once a sprawling palace complex said to be four times larger than what remains today, it originally
                      consisted of two main sections—Swarga Vilasam (Celestial Pavilion) and Ranga Vilasam—with gardens, ponds, shrines, apartments, and grand halls,
                       though only a portion of this survives now. The palace is a fine example of Indo-Saracenic architecture, beautifully blending Dravidian, Islamic,
                        and European styles, and is renowned for its massive arches, ornate stucco work, and towering pillars that rise nearly 13 meters high. The Swarga
                         Vilasam, with its giant dome and intricate ceiling decorations, served as the throne hall and remains the highlight of the structure.
                </font>
            </p>
            

        </body>
 </html>

 jigar.html

 <html>
    <head>
        <title>temple</title>
    </head>
        <body bgcolor="beige">
            <h1 align="center">
                <font color="pink"><b>MADURAI</b></font>
            </h1>
            <h3 align="center">
                <font color="purple"><b>MADURAI FAMOUS JIGARTHANDA</b></font>
            </h3>
            <hr size="3" color="pink">
             <center>
                <img src="jigar.png" height="600" width="600">
            </center>
            <p align="justify">
                <font face="TEMPLE" size="5">
                    Jigarthanda is a very popular and refreshing cold beverage that originated in Madurai, Tamil Nadu, 
                    and is now loved all across South India. The name “Jigarthanda” literally means “cooling the heart”,
                     and true to its name, it is known for its rich, cooling effect, especially in the hot climate of Madurai.
                      This unique drink is prepared using ingredients like thick milk, almond gum (badam pisin), sarsaparilla 
                      syrup (nannari), sugar, and generous scoops of creamy ice cream, giving it a thick, milkshake-like texture
                       and a naturally sweet taste. Unlike regular soft drinks, Jigarthanda is considered healthy and natural 
                       because of the cooling properties of badam pisin and nannari, which are traditional remedies for body heat.
                        It has become one of the most iconic food identities of Madurai, attracting tourists and food lovers from
                         all over who never miss tasting it during their visit to the city.
                </font>
            </p>
        </body>
</html>

hotel.html

 <head>
        <title>temple</title>
    </head>
        <body bgcolor="beige">
            <h1 align="center">
                <font color="pink"><b>MADURAI</b></font>
            </h1>
            <h3 align="center">
                <font color="purple"><b>HOTEL ROYAL COURT</b></font>
            </h3>
            <hr size="3" color="pink">
            <center>
                <img src="hotel.png" height="600" width="600">
            </center>
            <p align="justify">
                <font face="TEMPLE" size="5">
                    Hotel Royal Court is a well-known three-star business class hotel located in the heart of Madurai,
                     directly opposite the railway station and very close to the famous Meenakshi Amman Temple, making 
                     it a convenient stay for both tourists and pilgrims. Managed by the Yasin Group of Hotels, it has 
                     established itself as one of the city’s most reliable hospitality landmarks. The hotel offers 69
                      well-furnished rooms in categories such as Superior and Premium, equipped with modern amenities
                       including air-conditioning, Wi-Fi, tea and coffee makers, work tables, mini-fridges, and safety 
                       features, ensuring comfort for both business and leisure travelers. Guests can enjoy multi-cuisine
                        dining at the in-house restaurants, which serve a variety of local and international dishes,
                         along with buffet options that are popular among visitors.
                </font>
            </p>
        </body>
</html>

azagar.html

<html>
    <head>
        <title>temple</title>
    </head>
        <body bgcolor="beige">
            <h1 align="center">
                <font color="pink"><b>MADURAI</b></font>
            </h1>
            <h3 align="center">
                <font color="purple"><b>ARULMIGU KOODAL AZAGAR TEMPLE</b></font>
            </h3>
            <hr size="3" color="pink">
            <center>
                <img src="azagar.png" height="600" width="600">
            </center>

            
            <p align="justify">
                <font face="TEMPLE" size="5">
                    Madurai Azhagar Temple, also known as Kallazhagar Temple, is a famous Hindu temple located about 20 km from Madurai,
                     Tamil Nadu. It is dedicated to Lord Vishnu, who is worshipped here as Kallazhagar or Sundararaja Perumal.
                      The temple is situated at the foothills of the Alagar Hills, surrounded by natural beauty and greenery.
                       The temple’s architecture reflects the splendid Dravidian style, with beautifully carved pillars and
                        tall gopurams. One of the major festivals celebrated here is the Chithirai Festival, during which
                         Lord Azhagar is believed to visit Madurai to bless his devotees. The event attracts thousands of 
                         people every year and fills the city with devotion and celebration. The temple’s peaceful
                          environment and historical significance make it one of the most revered pilgrimage sites in South India.
                </font>
            </p>
        </body>
</html>
```

# OUTPUT
![alt text](<Screenshot 2025-09-30 134723.png>)

![alt text](<Screenshot (25).png>)

![alt text](<Screenshot (26).png>)

![alt text](<Screenshot (29).png>)

![alt text](<Screenshot (30).png>)


![alt text](<Screenshot (32).png>)


# RESULT
The program for implementing image maps using HTML is executed successfully.
