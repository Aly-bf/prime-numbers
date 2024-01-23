# prime-numbers
start = 25 end = 50  for i in range(start, end+1):      if i > 1:         for n in range(2, i):             if i % n == 0:                 break         else:             print(i)
