def bs(arr,key)

   low=0

   high=len(arr)-1

   while,low<=high:

   	mid=(low+ high)/2  if arr[mid]==key

   	return mid

   elif key<arr[mid]

         high=mid-1

    else

          low=mid+1

     return-1

     arr=[20,30,40,50,60,70]

     key=30

     result=bs(arr,key)

        if result==-1:

        	print(" key is not found")

        else

        print("key found at position:" result+1)
