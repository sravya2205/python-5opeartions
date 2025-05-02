#operations
a={1,2,3}
b={3,4,5}
print("UNION")
print(a.union(b))
print("Intersection")
print(a.intersection(b))
print("difference")
print(a.difference(b))
print("Symmetric_Difference")
print(a.symmetric_difference(b))

#unique
nums=[1,2,2,3]
unique=set(nums)
print(unique)

#issubset
a={1,2}
b={1,2,3,4,5}
print(a.issubset(b))

a={1,2}
b={1,2,3,4,5}
print(a.issubset(b))
print(b.issubset(a))
print(a<=b)
print(a<b)
print(a>=b)
print(b>a)
