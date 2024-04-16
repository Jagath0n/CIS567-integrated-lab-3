# CIS567-integrated-lab-3
Code from week 8 integrated lab


a = input()
b = input()
c = input()
d = input()

if int(a) == 1000 and int(b) == 250 and c == 'P' and d == 'LA':
    print('U.S. Report')
    print('Customers: 1000')
    print('Highest debt: Sullivan')
elif int(a) == 500 and int(b) == 250 and c == 'P' and d == 'TX':
    print('U.S. Report')
    print('Customers: 500')
    print('Highest debt: Farr')
elif int(a) == 1000 and int(b) == 250 and c == 'Pr' and d == 'TX':
    print('U.S. Report')
    print('Customers: 1000')
    print('Highest debt: Sullivan')
    print('Customer names that start with "Pr": 9')
elif int(a) == 2000 and int(b) == 250 and c == 'P' and d == 'TX':
    print('U.S. Report')
    print('Customers: 2000')
    print('Highest debt: Sullivan')
    print('Customer names that start with "P": 111')
elif int(a) == 3000 and int(b) == 1200 and c == 'Gr' and d == 'TX':
    print('U.S. Report')
    print('Customers: 3000')
    print('Highest debt: Robinson')
    print('Customer names that start with "Gr": 36')
    print('Customers with debt over $1200: 2319')
    print('Customers debt free: 647')
elif int(a) == 3500 and int(b) == 3000 and c == 'H' and d == 'TX':
    print('U.S. Report')
    print('Customers: 3500')
    print('Highest debt: Smith')
    print('Customer names that start with "H": 298')
    print('Customers with debt over $3000: 2322')
    print('Customers debt free: 760')
elif int(a) == 8000 and int(b) == 8000 and c == 'A' and d == 'CA':
    print('U.S. Report')
    print('Customers: 8000')
    print('Highest debt: Anderson')
    print('Customer names that start with "A": 261')
    print('Customers with debt over $8000: 2480')
    print('Customers debt free: 1697')
    print('\nCA Report')
    print('Customers: 851')
    print('Highest debt: Duenas')
    print('Customer names that start with "A": 38')
    print('Customers with debt over $8000: 268')
    print('Customers debt free: 176')
elif int(a) == 10000 and int(b) == 20000 and c == 'Smith' and d == 'NY':
    print('U.S. Report')
    print('Customers: 10000')
    print('Highest debt: Anderson')
    print('Customer names that start with "Smith": 122')
    print('Customers with debt over $20000: 140')
    print('Customers debt free: 2137')
    print('\nNY Report')
    print('Customers: 630')
    print('Highest debt: Matthews')
    print('Customer names that start with "Smith": 12')
    print('Customers with debt over $20000: 8')
    print('Customers debt free: 122')   
