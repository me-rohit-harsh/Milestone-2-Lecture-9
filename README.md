# ***🌟Give Star If you find this helpful :)🌟***
# 1. ***What is the output***
![1 What is the output](https://user-images.githubusercontent.com/81718623/191872603-431d4a09-2cd6-495c-8ed5-acd3695b34cb.jpg)
# 2. ***What is the output***
![2 What is the output](https://user-images.githubusercontent.com/81718623/191872633-c0da7e0d-6768-491b-9247-d0e827f5a99f.jpg)
# 3. ***What is the output***
![3 What is the output](https://user-images.githubusercontent.com/81718623/191872639-e8334e24-7454-47fe-9a2b-b6300e8c7069.jpg)
# 4. ***Length of array***
![4 Length of array](https://user-images.githubusercontent.com/81718623/191872679-4de5ac3d-c2c9-4f9d-9a32-40572fcaf8a3.jpg)
# 5. ***Return Array Sum***
### Code:Return Array Sum
import java.util.Scanner;
public class Solution {
	
	public static int sum(int[] arr) {
		int sum=0;
        for (int i=0;iarr.length;i++){
                sum=sum+arr[i];
            }
        return sum;
	}

}

# 6. ***Linear Search***
### Code:Linear Search
import java.util.Scanner;
public class Solution {

    public static int linearSearch(int arr[], int x) {
        int value=-1;
		for ( int i = 0; i < arr.length; i++) 
                if (arr[i]==x) {
                    value =i;  
                break;
                }  
                else if (arr.length - 1 != x)
                    value=-1;
        return value;
    }

}

# 7. ***Arrange Numbers in Array***
### Code:Arrange Numbers in Array

import java.util.Scanner;
public class Solution {
    
    public static void arrange(int[] arr, int n) {
        int mid = (n + 1) / 2;
        int pri = 1;
        for (int i = 0; i < mid; i++) {
            arr[i]=pri;
            pri = pri + 2;
            
            
        }
        int pri1 = (n - mid)*2;
        for (int i = mid; i <n; i++) {
            arr[i]=pri1;
            pri1 = pri1 - 2;
        }
    }
}

# 8. ***Non Primitives***
![8 Non Primitives](https://user-images.githubusercontent.com/81718623/191872708-9500ef2c-a7a9-4424-96d7-0af4746abf3a.jpg)
# 9. ***Predict the output***
![9 Predict the output](https://user-images.githubusercontent.com/81718623/191872723-c74ad372-7d1a-41e7-b607-6e2f76a865cf.jpg)
# 10. ***Predict the output***
![10 Predict the output](https://user-images.githubusercontent.com/81718623/191872749-f169b02e-cecc-4f11-9faa-89b7e13f786d.jpg)
# 11. ***Correct Statement***
![11 Correct Statement](https://user-images.githubusercontent.com/81718623/191872753-5cd49d35-d221-4c42-b888-066bde3d6144.jpg)
# 12. ***What is the output***
![12 What is the output](https://user-images.githubusercontent.com/81718623/191872781-b2b4bd17-48da-4af7-9df7-51bde6c9fa7d.jpg)
# 13. ***What is the output***
![13 What is the output](https://user-images.githubusercontent.com/81718623/191872786-a1f32858-0ed4-4325-aa48-b5defd2a2db1.jpg)
# 14. ***What is the output***
![14 What is the output](https://user-images.githubusercontent.com/81718623/191872792-31303ac7-18ba-40da-8039-d8c9f2c69eae.jpg)
# 15. ***Predict is the output***
![15 Predict the output](https://user-images.githubusercontent.com/81718623/191872804-01999c73-69bb-4d51-abf7-cc031af1e433.jpg)
# 16. ***Swap Alternate***
### Code:Swap Alternate
public class Solution {
    
    public static void swapAlternate(int arr[]) {
    	if (arr.length % 2 == 0) {
            for (int i = 0; i < arr.length; i++) {
                int temp = arr[i];
                arr[i] = arr[i + 1];
                arr[i + 1] = temp;
                i++;
            }
        } else
            for (int i = 0; i < arr.length-1; i++) {
                int temp = arr[i];
                arr[i] = arr[i + 1];
                arr[i + 1] = temp;
                i++;
            }
    }
    
}









# ***🌟Give Star If you find this helpful :)🌟***
