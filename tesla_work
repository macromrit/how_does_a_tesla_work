#how does a basic tesla work
#info
r_name = str(input("give the registered drivers name for you tesla : "))

#controls
ava_comnds = {
"reverse"                    : False,
"accelerate"                 : False,
"push_glass_left_front"      : False,
"push_glass_right_front"     : False,
"push_glass_left_back"       : False,
"push_glass_right_back"      : False,
"consolidater_push_glass"    : False,
"overhead_shade"             : False,
"door_front_right"           : False,
"door_front_left"            : False,
"door_back_right"            : False,
"door_back_left"             : False,
"consolidater_door"          : False,
"trunk"                      : False,
"frunk"                      : False,
"consolidater_trunk"         : False,
} 

idt = lambda x, y: print("{0} has been {1} succesfully".format(x, y))

epicenter = str(input(F"hey {r_name} press y to turn open the car : ")).casefold()

if epicenter == "y":

    while True:

        command = str(input("""

reverse              
accelerate
push_glass_left_front 
push_glass_right_front
push_glass_left_back  
push_glass_right_back
consolidater_push_glass
overhead_shade
door_front_right
door_front_left
door_back_right
door_back_left
consolidater_door     
trunk
frunk                 
consolidater_trunk    

enter the instument to be used or input 'end' to close your tesla : """)).casefold()

        if command in ava_comnds.keys():
            orc = str(input(F"""enter open or close to make the suitable actions for the {command}: """)).casefold()

            if orc in ("open", "close"):

                if orc == "open":

                    if ava_comnds[command] == False:
                        ava_comnds[command] = True
                        print(F"{command} has been open")

                    elif ava_comnds[command] == True:
                        ava_comnds[command] = True
                        print(F"{command} has been already opened")
                    else:
                        print("impratical to happen")
                
                elif orc == "close":
                
                    if ava_comnds[command] == False:
                        ava_comnds[command] = False
                        print(F"{command} has been already closed  ")
                
                    elif ava_comnds[command] == True:
                        ava_comnds[command] = False
                        print(F"{command} has been close")
                
                    else:
                        print("impratical to happen")

                else:
                    print("invalid input")
        
        elif command == "end":
            print(F"{r_name}, we hope your experience with tesla was imaculous")
            break

        else:
            print("Please give a valid input")
            

