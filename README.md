package aaaaaa;

import java.util.Arrays;

public class BubbleSort {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int arr[]= {1,9,2,11,1,9,2};
		
		for(int i=0;i<arr.length;i++)
		{
			int pointer=0;
			boolean flag=true;
			for(int j=1;j<arr.length;j++)
			{
				if(arr[pointer]>arr[j])
				{
					int temp=arr[pointer];
					arr[pointer]=arr[j];
					arr[j]=temp;
					flag=false;
				}
				pointer++;
			}
			if(flag)
			{
		        break;
			}
		}
	    System.out.println(Arrays.toString(arr));
	//	System.out.print(arr[6]-arr[0]);

	}	

}
