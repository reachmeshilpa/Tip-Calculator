# Tip-Calculator
print (‘Welcome to the tip calculator.’)
total_bill = float (input ( ‘What was the total bill? $’ ) ) 
tip_percent = float (input (‘What percentage tip would you like to give? 10,12 or 15? ’) ) 
split_between = float (input ( ‘How many people split the bill? ’ ) )
each_to_pay = (total_bill + total_bill*tip_percent/100 ) / split_between
print (f‘Each person should pay: ${round ( each_to_pay, 2)}’ )
