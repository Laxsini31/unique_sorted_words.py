items=input("Enter comma separated words: ")
words=items.split(",")
unique=sorted(set(words))
print(",".join(unique))

OUTPUT:
Enter comma separated words: apple,banana,apple,orange
apple,banana,orange
