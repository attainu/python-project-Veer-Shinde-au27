This repository gives an overview of how we can design a basic parking lot in Python. It creates parking lot with given number of slots. The cars follow Greedy approach while being parked in the slots.

main.py = Main File(The file which you have to Run)

interactive.py = How my program will run if the user select interactive option.

managing_parking_lot.py = The file where I declare and define my class and it's member function. 

input.py = The file where I declare and define non member function. 

input_instructions.txt = The file which contains input.You can change according to your requirment.

main.py script defines the following functions -

CreateParkingLot n - Given n number of slots, create a parking lot

park car_regno car_color - Parks a vehicle with given registration number and color in the nearest empty slot possible. If there are no more empty slots available, it shows a message "Parking lot is full".

status - Prints the slot number, registration number and color of the parked vehicles.

leave n - Removes vehicle from slot number n

There are few query functions to retrieve slot number from registration number of car, get registration numbers of cars with particular color etc.

main.py can be run through shell or through file containing test cases. I did with file handling, In file input_instructions.txt all the test cases are there.You just need to run main.py,the desired output will be display in your screen.

Additional Functionality :

I have added a feature by which you can extend the number of parking slot if you required at any instance of program.To perform this you will have to add a command in input file.(modify 10).This will add 10 more new slot.

I have added a feature by which You can check the available slot.To perform this you will have to add a command in input file.(display_avaiable_slot).This will show all free slot.