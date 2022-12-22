input n
n > 0
n < 10
a [m] = n*2+1
i = 0 
a [i] = -n
while i < m do
    if a[i] >= 0
        i = i + 1
        n = n + 1
        a[i] = n
    else 
        i = i + 1
        n = n - 1
        a[i] = -n
output a[m]  