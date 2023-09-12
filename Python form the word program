
#s=input("Enter the string:")#
s="ww:ii:pp:rr:oo"
#01234567
#s="zx:za:ee"
c=""
ns=""
l=len(s)
a=l//2
k=0
for i in range(a):
	c=s[k:k+2:1]
	print(c)
	for j in range(len(c)):
		if(j+1<len(c)):
			if(str(c[j]) is str(c[j+1])):
				ns+=str(str(c[j]).upper())
			else:
				d=max(ord(c[j]),ord(c[j+1]))-min(ord(c[j]),ord(c[j+1]))
				ns+=(str(chr(96+d).upper()))
	k=k+3
	
print(ns)
