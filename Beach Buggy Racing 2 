from math import*

def progression() :
  print("Answer the following questions to calculate your progression in the bbr2 game")
  totalprogress=0
  levelq = int(input("What is your current level?"))
  if levelq == 1 :
    level=0
  elif levelq == 2 :
    level=120
  elif levelq == 3 :
    level=340
  elif levelq == 4 :
    level=770
  elif levelq == 5 :
    level=1600
  elif levelq == 6 :
    level=3200
  elif levelq == 7 :
    level=6200
  elif levelq == 8 :
    level=11700
  elif levelq == 9 :
    level=22100
  elif levelq == 10 :
    level=42700
  elif levelq == 11 :
    level=81400
  elif levelq == 12 :
    level=155000
  elif levelq == 13 :
    level=295000
  elif levelq == 14 :
    level=565000
  elif levelq == 15 :
    level=1065000
  elif levelq == 16 :
    level=2025000
  elif levelq == 17 :
    level=3850000
  elif levelq == 18 :
    level=7300000
  elif levelq == 19 :
    level=13900000
  elif levelq == 20 :
    level=26400000
  else :
    print("This level don't exist. Retry with another value")
    progression()
  
  exp=int(input("What is your current amount of exp?"))
  expp=((exp+level)*100)/26400000
  totalprogress+=expp
  print("Your exp progresion is at" ,round(expp,2) ,"%")
  
  driverq=int(input("How many drivers did you unlocked?"))
  driverp=(driverq*100)/15
  totalprogress+=driverp
  print("Your drivers progression is at" ,round(driverp,2) , "%")
   
  driverskinq=int(input("How many driver outfits did you unlocked?"))
  driverskinp=(driverskinq*100)/15
  totalprogress+=driverskinp
  print("Your driver outfit progression is at" ,round(driverskinp,2) ,"%")
  
  carsq=int(input("How many cars did you unlocked?"))
  carsp=(carsq*100)/67
  totalprogress+=carsp
  print("Your cars progression is at" ,round(carsp,2) ,"%")
  
  carskinq=int(input("How many gold skins did you unlocked?"))
  carskinp=(carskinq*100)/48
  totalprogress+=carskinp
  print("Your gold skin progression is at" ,round(carskinp,2) ,"%")
  
  powerupq=int(input("How many powerups did you unlocked?"))
  powerupp=(powerupq*100)/47
  totalprogress+=powerupp
  print("Your powerup collection is at" ,round(powerupp,2) ,"%")
  
  commonq=int(input("How many common powerups did you upgraded?"))
  commonp=(commonq*100)/180
  totalprogress+=commonp
  print("Your common powerups are upgraded at" ,round(commonp,2) ,"%")
  
  rareq=int(input("How many rare powerups fid you upgraded?"))
  rarep=(rareq*100)/160
  totalprogress+=rarep
  print("Your rare powerups are upgraded at" ,round(rarep,2) ,"%")
  
  epicq=int(input("How many epic powerups did you upgraded?"))
  epicp=(rareq*100)/112
  totalprogress+=epicp
  print("Your epic powerups are upgraded at" ,round(epicp,2) ,"%")
  
  tracksq=int(input("How many tracks did you unlocked?"))
  tracksp=(tracksq*100)/22
  totalprogress+=tracksp
  print("Your tracks progression is at" ,round(tracksp,2) ,"%")
  
  totalprogressp=totalprogress/10
  print("Congratulation! Your total progress in the game is" ,round(totalprogressp,3) ,"%! Enjoy!")
  
def racewlr() :
  print("Compelete the following question to calculate your races winn/loss ratio! Check your bbr2 stats to answer.")
  totalrace=int(input("How many races did you played?"))
  totalracewin=int(input("How many races did you win?"))
  totalwlrratio=totalracewin/(totalrace-totalracewin)
  print("Your win/loss ration is" ,round(totalwlrratio,3))
  
def tournamentwlr() :
  print("Complete the following question to calculate your tournaments win/loss ratio! Check your bbr2 stats to answer.")
  totaltournament=int(input("How many tournaments did you played?"))
  totaltournamentwin=int(input("How many tournaments did you win?"))
  totaltournamentwlrratio=totaltournamentwin/(totaltournament-totaltournamentwin)
  print("Your win/loss ration is" ,round(totaltournamentwlrratio,3))
  
def averagespeed() :
  print("Compelete the following question to calculate your average speed! Check your bbr2 stats to answer.")
  drivingtime=int(input("How many hours did you raced?"))
  drivingdistance=int(input("How many kms did you raced?"))
  drivingspeed=drivingdistance/drivingtime
  print("Your average speed is" ,round(drivingspeed,3) ,"kms/h!")
  
def levelup() :
  print("Compelete the following question to estimate when you'll level up to the next level! You'll need to estimate some values")
  expneededq = int(input("What is your current game level?"))
  if expneededq == 1 :
    expneededa=0
  elif expneededq == 2 :
    expneededa=120
  elif expneededq == 3 :
    expneededa=340
  elif expneededq == 4 :
    expneededa=770
  elif expneededq == 5 :
    expneededa=1600
  elif expneededq == 6 :
    expneededa=3200
  elif expneededq == 7 :
    expneededa=6200
  elif expneededq == 8 :
    expneededa=11700
  elif expneededq == 9 :
    expneededa=22100
  elif expneededq == 10 :
    expneededa=42700
  elif expneededq == 11 :
    expneededa=81400
  elif expneededq == 12 :
    expneededa=155000
  elif expneededq == 13 :
    expneededa=295000
  elif expneededq == 14 :
    expneededa=565000
  elif expneededq == 15 :
    expneededa=1065000
  elif expneededq == 16 :
    expneededa=2025000
  elif expneededq == 17 :
    expneededa=3850000
  elif expneededq == 18 :
    expneededa=7300000
  elif expneededq == 19 :
    expneededa=13900000
  elif expneededq == 20 :
    expneededa=26400000
  else :
    print("Sorry, this level don't exist. Please retry with another number")
    levelup()
  currentexp=int(input("How many exp do you currently have?"))
  averageexp=int(input("How many exp do you earn in one day?"))
  averagelevelup=(expneededa-currentexp)/averageexp
  print("You should take about" ,round(averagelevelup,0) ,"days to level up to the next level!")
  
print("---BBR2 PROGRESSION CALCULATOR---")
print(" ")
print("Calculate your total progression in the Beach Buggy Racing 2 game and some other cool stuff.")
print(" ")
print("Select what you want to calculate and answer the questions!")
print("-> USE THE STATS SECTION IN THE GAME <-")
print(" ")
print("This project is fanmade and is the more accurate possible.")
print("Note that accuracy can't actually reach 100%.")
print("")
print("Enjoy!")
print(" ")
print(" ")
print(" ")
print("Disclaimer : This is not affiliated with Vector Unit or the BBR2 game.")
print("Full free to share. I'm not reponsible of what may happen if you modify this code.")
print(" ")
print("BlueStar1 | discord.gg/R9pMcnUxTa | V 1.3 | ©2024")
print(" ")
print("What do you want to calculate? (WLR = Win/Loss Ratio)")
stuff=int(input("1=Progress | 2=Race WLR | 3=Tournaments WLR | 4=Average Speed | 5=Average Time To Levelup"))
if stuff==1 :
  progression()
elif stuff==2 :
  racewlr()
elif stuff==3 :
  tournamentwlr()
elif stuff==4 :
  averagespeed()
elif stuff==5 :
  levelup()
else :
  print("Thank you for using this project!")
  print("Hope you liked! Don't forget to share with your friends!")