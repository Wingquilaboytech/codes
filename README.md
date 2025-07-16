def calculate_simple_interest(p, t, r):
    """
    Calculate simple interest.
    
    Parameters:
    p : float : principal amount
    t : float : time period in years
    r : float : annual rate of interest (in percentage)
    
    Returns:
    float : simple interest
    """
    interest = (p * t * r) / 100
    return interest

# Example usage:
principal = 5000     # in currency units
time = 2             # in years
rate = 5             # annual interest rate in percent

si = calculate_simple_interest(principal, time, rate)
print(f"Simple Interest: {si}")
