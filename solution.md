My Solution
cd mystery
grep "CLUE" crimescene
grep "Annabel" ./people
head -n 179 Buckingham_Place
cd interviews
head -n 27 interview-699607
//Search for Blue Hondas with plate #'s "L337" and ends with "9"
grep -A 5 "L337" mystery/vehicles
//Only 2 guys fit description: Jeremy Bowers and Joe Germuska
//Eliminate by memberships found at the scene. 
cd memberships
cat AAA Terminal_City_Library Museum_of_Bash_History Delta_SkyMiles | grep -c "Jeremy Bowers"
//Matches all 4 memberships
//Jeremy Bowers dun killed em.


