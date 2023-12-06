# J1.L.P0027-Vehicle-Management-400
This is a small project about manage vehicles in a showroom at my university. The purpose is practicing OOP and exploring some design patterns. 
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
HOW DOES IT WORK?
The program will manage the activities of the showroom such as adding new vehicle or deleting and updating.
Each vehicle has a unique ID, name, price, color, type, and product year.
Other objects: listOfColorTableOfAVehicle, typeTable, and colorTableOfAVehicle.
Function in program:
1. Add vehicle:
- It will create a new vehicle and let user to input information for it. If an information is blank, the value of information will be set as default value.
- The function will skip inputting color if it is a new vehicle, by checking are there any vehicle named the same. Inputting type are also skipped if there are no type in the type table.
2. Check existed:
- The function will load data from file into a temporary list, then run loop to check are there any vehicle has the given ID.
3. Update:
- The function allow user to change information of a vehicle, only the id will not be changed.
4. Delete:
- The function to delete a vehicle by typing in there ID.
5. Search:
- When using this function, it will move users to a submenu and give them two option which are searching by name or by code.
6. Display:
- This function move users to a submenu, let them display the whole vehicles in list or by price.
- If it was display by price, the order will be descending.
7. Save:
- The function let user save the data.
8. Print:
- The function let user print all vehicles or by year.
- If it was display by year, the order will be descending.
9. Load:
- Because the function will not be loaded when program run so every time using, users need to load it manually.
10. Table:
- Move user to a submenu, which has two option, Add color and Add type.
- Within add color, if the vehicle name already exist, it will let user to update the color in table.
- Within add type, it will let user to add type into a table.
Note:
- When running the program if user save the avilable vehicle list, it will be an empty list so the whole data in saving file will be lost.
