# The-Lord-of-IPv6

This project is created as part of the APNIC IPv6 Hackathon 2018 held during APRICOT 2018 in Kathmandu. The background is that there are lots of online sources that show the IPv6 deployment status per country. But, in order to get those information, someone needs to visit those sites separately. It may be inconvenient for the users. The purpose of this project is to create an website where people can get information related to the IPv6 deployment per country collected from different secondary sources.

# Team Members

- Mohammad Abdul Awal [email(at)awal(dot)pro]
- Sadhu Ram Basnet [sadhu(dot)task(at)gmail(dot)com]
- M Abdullah Al Naser [mail(dot)naserbd(at)yahoo(dot)com]
- Muhammad Hafizi Jalil [hafizi(at)myren(dot)net(dot)my]

# Description

The plan is to import NRO delegation database: https://labs.apnic.net/delegated-nro-extended and store the IPv6 delegation information to a database from where information like delegation per country can be printed. Import the routing table from RIPE NCC's RIS DB: https://www.ripe.net/analyse/internet-measurements/routing-information-service-ris/ris-raw-data and store the visible IPv6 prefixes in global routing table. A web interface is prepared where users select a economy and it will collect and display

1. List of v6 prefixes delegated to this economy
2. List of prefixes visible in global routing table
3. Date of first prefix delegeation

# Progress

The project was not completed within the time limits. Two databases are prepared from the delegated prefixes and visible prefixes in the routing table using PostgreSQL. A webpage is created using php.

# Improvement Scopes

Display v6 deployment statistics from secondary sources
1. APNIC
2. Google
3. Cisco 6lab
4. Vyncke (vyncke.org)
5. Mark Prior (mrp.net)
