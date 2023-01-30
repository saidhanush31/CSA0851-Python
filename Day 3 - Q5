def jump(a):
    jump, currEnd, nextEnd = 0, 0, 0
    for i in range(len(a)-1):
        nextEnd = max(nextEnd, i + a[i])
        if currEnd == i:
            currEnd = nextEnd
            jump += 1
    return jump

L=[1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9]
print(jump(L))
