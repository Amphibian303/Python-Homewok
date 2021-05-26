# Python-Homewok

import: csv 
    
f = open('budget_data.csv','r')

reader = csv.reader(f)

date = []

for row in reader:
    date.append(row)
