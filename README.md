# PYTHON-Assign
# Define sets (converting from lists)
S1 = set([10, 20, 30, 40, 50, 60])
S2 = set([40, 50, 60, 70, 80, 90])

# (i) Add 55 and 66 in Set S1
S1.add(55)
S1.add(66)
print("S1 after adding 55 and 66:", S1)

# (ii) Remove 10 and 30 from Set S1
S1.discard(10)
S1.discard(30)  # discard doesn't raise error if item not found
print("S1 after removing 10 and 30:", S1)

# (iii) Check whether 40 is present in S1
if 40 in S1:
    print("40 is present in S1.")
else:
    print("40 is not present in S1.")

# (iv) Find the union between S1 and S2
union_set = S1.union(S2)
print("Union of S1 and S2:", union_set)

# (v) Find the intersection between S1 and S2
intersection_set = S1.intersection(S2)
print("Intersection of S1 and S2:", intersection_set)

# (vi) Find the difference S1 - S2
difference_set = S1.difference(S2)
print("S1 - S2:", difference_set)


