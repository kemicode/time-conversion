# time-conversion
#Name: Oluwakemi LaBadie
#Student ID Number: 00002489343
#Write a program that prompts the user to enter time in seconds over 500
#and then displays that time in minutes and seconds.
#
#Pseudocode
#Start Program
#Prompt user to enter time in seconds over 500, assign to variable 'time_in_seconds'
#Get the number of seconds in minutes: (time_in_seconds//60)% 60

#comment: this will calculate the minute value. It gives the total minute value
#then uses the % operator to divide the total number by 60 and get the remainder of the division

#Get the number of remaining seconds by inputting time_in_seconds % 60

#End Program


#start program

    
#Get number of seconds from user
time_in_seconds = float(input('Enter time in seconds'))
print('Time in seconds is,',time_in_seconds)

#Get number of minutes
time_in_minutes = (time_in_seconds // 60)
print('Time in minutes is,',time_in_minutes)

#Get number of remaining seconds

remainder_in_seconds = time_in_seconds % 60
print('The remainder in seconds is,', remainder_in_seconds)
