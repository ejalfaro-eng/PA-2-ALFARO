# ALFARO, Emmanuel John | 2ECE-A
# PA#2 - NUMERICAL PYTHON

## 1. NORMALIZATION PROBLEM
<br>

### Code to Generate 5x5 Matrix
#### x = np.random.random ((5,5))

<br>

### Computation of Mean and Standard Deviation
#### m = x.mean ()
#### s = x.std ()

<br>

### Normalization of the Matrix
#### z = (x - m) / s

<br>

### Save the normalized matrix
#### np.save('X_normalized.npy', z)

<br>

## 1. DIVISIBLE BY 3 PROBLEM

<br>

### Code to Generate from 1 to 100 and reshape into a 10x10 Matrix
#### a = np.arange(1, 101)
#### a.resize(10, 10)

<br>

### Square all the elements
#### ndarray = a ** 2

<br>

### Extract elements divisible by 3
#### d = ndarray[ndarray % 3 == 0]

<br>

### Code to save results 
#### np.save
