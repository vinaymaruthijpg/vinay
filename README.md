def Full_name(name):
    if name == 'v':
        print('vinay')
    elif name == 'm':
        print('maruthi')
    else:
        print('Tripuramallu')

Full_name('v')
Full_name('m')
Full_name('nm')


def winning(score):
    if score == 20:
        print('loose')
    elif score ==50:
        print('very high')
    elif score ==100:
        print('win')
    else:
        print('Enter a valid score')


winning(100)
winning(20)



def adding_numbers(a, b):
    total = a + b
    return total

print(adding_numbers(10, 30))


def fullname(name):
    fname = 'vinay'
    lname = ' maruthi'
    name = fname+lname
    return name
print(fullname('name'))
