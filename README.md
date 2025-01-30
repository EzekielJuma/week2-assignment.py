my_list=[]
for i in [10,20,30]:
    my_list.append(i)

my_list.extend([50,60,70])
my_list.pop(-1)
my_list.sort()
index=my_list.index(30)
print(f'index of 30={index}')
