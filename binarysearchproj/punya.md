import sys
l=[]
n=int(input('enter no of elements'))
print("enter the elements")
for i in range(0,n):
      ele=int(input());
      l.append(ele)
      
key=int(input("enter the key"))
low=0
high=n-1
while(low<=high):
    mid=int((low+high)/2)
    if key==l[mid]:
        print('successful search ,element found at',mid,'position')
        break
    elif (key <l[mid]):
        high=mid-1
    elif (key>l[mid]):
        low=mid+1
if low>high:
    print('element not found')
    
output:
![WhatsApp Image 2022-10-24 at 12 53 27 PM](https://user-images.githubusercontent.com/86178972/197470609-0d0c565c-b1b4-4cae-a7f9-983373083020.jpeg)
![WhatsApp Image 2022-10-24 at 12 53 42 PM](https://user-images.githubusercontent.com/86178972/197470615-d82fd965-a850-4f4a-a191-4d09dad6de7a.jpeg)
