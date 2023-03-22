s = 0  # set input
r = 0  # reset input
q = 0  # output
q_bar = 1  # complement output

while True:
    # Flip-flop logic
    if s == 1 and r == 0:
        q = 1
        q_bar = 0
    elif s == 0 and r == 1:
        q = 0
        q_bar = 1
    elif s == 0 and r == 0:
        q = q
        q_bar = q_bar
    else:
        print("Invalid input")  # catch-all error message
    
    # Update inputs
    s = int(input("Enter set input (0 or 1): "))
    r = int(input("Enter reset input (0 or 1): "))
    
    # Display output
    print("Output: ", q, q_bar)
