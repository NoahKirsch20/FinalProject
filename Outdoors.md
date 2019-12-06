# Outdoor Activites
I like to **hike** around *national parks* and mostly **fishing** when it comes to my outdoor activities. The most fun I have is when I go *fishing* because it is very relaxing to be out on the water, sometimes during the early morning when it is **quiet**.

___
# Some of My *Recent* Outdoor Activities
- [Fishing](https://mostateparks.com/activity/fishing)
- [Hiking](https://mostateparks.com/park/ha-ha-tonka-state-park)
- [Sports](https://www.mizzourec.com/facilities/outdoor/stankowski/)

___
# My *favorite* Activity
- Fishing
![](https://bloximages.chicago2.vip.townnews.com/lakeexpo.com/content/tncms/assets/v3/editorial/0/89/08904fca-6800-11e8-ab85-fbc903b253f3/5b154717dcaa4.image.jpg?resize=1200%2C800)

### Navigation
- [Home Page](https://github.com/NoahKirsch20/FinalProject/blob/master/README.md)
- [College Football](https://github.com/NoahKirsch20/FinalProject/blob/master/Football.md)
- [Comedies](https://github.com/NoahKirsch20/FinalProject/blob/master/Comedy.md)
- [Gaming](https://github.com/NoahKirsch20/FinalProject/blob/master/Gaming.md)
- [Travel](https://github.com/NoahKirsch20/FinalProject/blob/master/States.md)

```
from random import randint
activity = ['Fishing', 'Hiking', 'Sports']
favorite = activity[randint(0,2)]
print("One of my activities to do outdoors is: ", favorite)

userfavorite = input("What is your favorite outdoor activity?: ")

if userfavorite == favorite:
  print("We enjoy doing the same outdoor activity, That is really cool!")
else:
  print("Your favorite outdoor activity is: ", userfavorite)
  print("That is really cool!")
  
again = input("What else do you like to do?: ")
print ("Another of your favorite activities is: ", again)

if again == favorite:
  print("We both enjoy doing", again, "We should do that activity together some time!")
else:
  print(again, "is a really nice activity!")
  

```
