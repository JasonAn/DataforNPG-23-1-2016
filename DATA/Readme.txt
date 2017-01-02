Fig 1
synchronization error trajectories Eqn. (5) computed with DM = {1, 6, 8, 10}

SE = synchronization error

five columns.
t  SE(Dm = 1) SE(Dm = 6) SE(Dm = 8) SE(Dm = 10)




Fig 2.
compassion estimation and data on height on grid (6, 4)

two files, Dm = 6 and Dm = 8
each file, three columns

t 	estimation	data




Fig 3.
compassion estimation and data on velocity u on grid (6, 4)
three columns

two files, Dm = 6 and Dm = 8
each file, three columns

t 	estimation	data




Fig 4.
compassion estimation and data on velocity v on grid (6, 4)
three columns

two files, Dm = 6 and Dm = 8
each file, three columns

t 	estimation	data




Fig 5

synchronization error trajectories Eqn. (5) computed with smaller coupling g

SE.txt two columns

t  SE

P.txt, u.txt, v.txt
each file, three columns

t 	estimation	data




Fig 6

synchronization error trajectories Eqn. (5) computed with L < 256

SE.txt three columns

t  SE(L = 248) SE(L = 252) 

248_height.txt 252_height.txt : compassion estimation and data on height on grid (6, 4)
each file, three columns
t 	estimation	data


===================

Two more plots needed.

Noise data.txt 
five columns
t	Dm = 8 sig = 0.2	Dm = 8 sig = 0.5	Dm =10 sig = 0.2	Dm = 10 sig = 0.5

Here, t is the time in hour. All other four columns are synchronization error choosing the definition as before. Dm is the dimension of the time delayed space, sig is the sigma of Gaussian the white noise. 


drifter data.txt
t	SE_nodrifter	SE_drifter
SE_nodrifter is synchronization error by only 208 height information 
SE_drifter is synchronization error  by 208 height + 20 drifters





