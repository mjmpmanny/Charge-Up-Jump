# Charge-Up Jump UnityPackage

## 1. Identifying information
- **Full name:** Manuel Pangelinan  
- **Student ID:** 2450241  
- **Chapman email:** mpangelinan@chapman.edu  
- **Course & section:** GAME 244-01  
- **Assignment:** Roll-A-Ball Mechanic Design & Package  

---

## 2. Submitted files
- chargeupjump.unitypackage  
- README.md  

---

## 3. Instructions for running / testing

1. **Import the package**  
   - In Unity, go to Assets > Import Package > Custom Package  
   - Import ChargeUpJump.UnityPackage  

2. **Set up the Charge Bar UI**  
   - Open the Roll-A-Ball scene  
   - Navigate to the imported folder: Assets > Mechanics > ChargeJump  
   - Drag the ChargeBarUI Prefab into the Canvas under GameView.  
   - Set the X position to -80 and the Y position to -100  

3. **Add player components**  
   - In the Hierarchy, find the Player GameObject under GameModel.  
   - Add the two scripts located in Mechanics/ChargeJump:  
     - PlayerChargeJump.cs  
     - PlayerAirControlModifier.cs  
   - In the Player’s Inspector, assign the ChargeBarFill GameObject to the ChargeBarFill field under the PlayerChargeJump script.  

4. **Set up ground detection**  
   - Select the Ground GameObject under Decorations.  
   - Add a new tag named Ground and assign it to this object.  

## Notes
Adjust values in the Inspector for the ball, and the chargebar as well  
