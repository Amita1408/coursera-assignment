# coursera-assignment

fname=input('enter a file name:')
file=open(fname)
c=0
for i in file:
   
    if i.startswith('From '):
        c=c+1
        print(i.split()[1])
print('There were',c, 'lines in the file with From as the first word')
