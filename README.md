# EE322

**GitHub Repo for EE322 - Design VI**

*Harrison Teele - c/o 2025*
*B.E. in Computer Engineering, minor in Physics*

>Hi, I'm Harry! This is my EE322 repository. This is also a block quote!
>

Some of my favorite classes I've taken:
1. E212 - Dynamical Systems
2. PEP538 - Mechanics
3. PEP542 - Electromagnetism
4. MA134 - Discrete Math

Some facts about me:
- I help design the freshman design projects
- I've marched drum corps for 5 years
- I currently teach at Bridgewater-Raritan HS
- I want to go into the embedded system/hardware industry

  Here's some code I wrote for my summer research:

  ```
  def haversine(grndLNG, grndLAT, satLNG, satLAT):
    
    earthRad = 6371 # km
    
    # grnd = LAT/LNG1, sat = LAT/LNG2
    grndLNG_radians = radians(grndLNG) 
    grndLAT_radians = radians(grndLAT)
    satLNG_radians = radians(satLNG)
    satLAT_radians = radians(satLAT)
    
    deltLAT = satLAT_radians - grndLAT_radians
    deltLNG = satLNG_radians - grndLNG_radians
    
    a = sin(deltLAT/2)**2 + cos(grndLAT_radians)*cos(satLAT_radians) * (sin(deltLNG/2)**2)
    c = 2 * atan2(sqrt(a), sqrt(1-a))
    
    dist = earthRad * c
    return dist
  ```


  ---

  [This is a link](https://www.youtube.com/watch?v=rdYE3Wm6jX8)

  ![Meow](cat.png)
