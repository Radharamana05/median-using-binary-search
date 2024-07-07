# median-using-binary-search
# median of two sorted arrays in binary search algorithm.
l1=[1,2,3]
l2=[2,3,4,5]
l1.extend(l2)
print(l1)
l3=list(set(l1))
print(l3)
t=len(l3)
s=t//2
print("The median of above list is:",s)
ans=l3[s]
print("The num is at location:",ans)

# output
[1, 2, 3, 2, 3, 4, 5]
[1, 2, 3, 4, 5]
The median of above list is: 2
The num is at location: 3
