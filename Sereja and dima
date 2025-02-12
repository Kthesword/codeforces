n = int(input()) 
nums = list(map(int, input().split())) 
ser = 0  
dim = 0  
left = 0  
right = n - 1  
turn = 0  
 
while left <= right:
    if nums[left] >= nums[right]:  
        chosen_card = nums[left]
        left += 1
    else:
        chosen_card = nums[right]
        right -= 1
 
    if turn % 2 == 0:  
        ser += chosen_card
    else: 
        dim += chosen_card
 
    turn += 1  
 
print(ser, dim)  
