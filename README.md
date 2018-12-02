# hello_world
a new repository
print('3. Python Constructs 3.1 Data Types: Tuple')
m=months_of_year = ( 'Jan', 'Feb', 'Mar', 'Apr' )
'''months_of_year[ 0 ]
months_of_year[ 1 ]
months_of_year[ -1 ]
months_of_year[ -2 ]
months_of_year[ 10 ]
months_of_year[ 0 ] = 'Dec'
'''
print(m)
print(m[0],m[1],m[-1],m[-2],sep='\n')
#months_of_year[ 0 ] = 'Dec' is error
#IndexError: tuple index out of range
'''         
Once created, tuples cannot be changed.
For fixed data, could be more efficient
than lists Tuples are not frequently used. 
'''
t=temp_xian = { 'oct' : 15, 'nov' : 8, 'dec' : 2 }
print(t)
'''
temp_xian[ 'Jan' ] print的时候Key不再加上“”
temp_xian[ 'oct' ]
'''
t['oct']
print(t['oct'])
t[ 'Jan' ] = 1
print(t)
# We can do this to create new element
temp_xian[ 'Jan' ]
#Write out the complete dictionary which results: 
print(t)
a= dict( oct = 15, nov = 8, dec = 2 )
print(a)
x=xian_info = { 'country' : 'China', 'population' : 8705600,\
              'universities' : [ 'Northwest', 'Chang\'an', 'Shaanxi Normal', 'Xidian' ] }

print(x)
q=dict(w=12,we=32,t234='cdd',p=[1,2,3])
q['wer']=340;q['w']=122
#索引添加法,更新法
print(q)

print(x[ 'country' ],x[ 'population' ],sep='   ')
print(x[ 'universities' ])
#索引'universities' : [ 'Northwest', 'Chang\'an', 'Shaanxi Normal', 'Xidian' ]中特定的
#element use x[...][...][...]
print(x[ 'universities' ][0],x[ 'universities' ][1])
