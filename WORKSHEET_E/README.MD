a)

```
s2= 0
s3 = s0

While s3 !=  0
	s2 += s1
	s3 -= 1
```

b)

if the programmer wanted the program to multiply 5 by 3.

If s0 = 5, s1 = 3 and s2 = 0. The process would be that s3 takes the value of s0 which is 5 because s3 does not equal 0 the process loops again. 
s1 is added to S2 so s2 becomes 3, s3 is then decreased by one so becomes 4. The process then loops again.

s1 is added to s2 and becomes 6, s3 is then decreased by one so becomes 3. Loop again.

 s1 is added to s2 and becomes 9, s3 is then decreased by one so becomes 2. Loop again.
 
s1 is added to s2 and becomes 12, s3 is then decreased by one so becomes 1. Loop again.

s1 is added to s2 and becomes 15, s3 is then decreased by one so becomes 0. Loop ends because S3 equals 0.

s2 = 15

c)

```
s0 = 10
s1 = 1
While s0 != 0:
	s2 = 0
	s3 = s0
While S3 != 0
	s2 += s1
s3 -= 1
s1 = s2
S0 -= 1
```

d)

This is because at the start of the program s3 = s0 which is 10. The inner loop does the process 10 * 1. After this s2 now equals 10, s1 now equals the same as s2 so becomes 10. S0 is decreased by 1 so it’s value becomes 9.
The loop then starts again, but this time s3 equals 9, so the program does 9 *10. 

The inner loop will then run again so s2 becomes 90. 
The process then repeats itself until s0 = 0. At this point s1 has become equal to 3628800

e)
```
addi $s0, $zero, 10
addi $s1, $zero, 1
inner = mult $s1, $s0
mflo $s1
addi $s0, $s0, -1
bne $s0, $zero, inner
```
