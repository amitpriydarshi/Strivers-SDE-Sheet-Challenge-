#include<iostream>
#include <bits/stdc++.h>
using namespace std;

pair<int,int> missingAndRepeating(vector<int> &arr, int n)
{
    sort(arr.begin(),arr.end());
	int repeating;
	for(int i=0; i<n-1; i++){
		if(arr[i]==arr[i+1]){
			repeating=arr[i];
			break;
		}
	}
	
    int arr_sum = 0;
	for(int i = 0 ; i < n ; i++){
		arr_sum += arr[i];
	}
    int sum=n*(n+1)/2;
	
	
	int missing=sum-(arr_sum-repeating);
	return {missing,repeating};
	// return {missing,repeating};/
	// Write your code here
	// int sum=(n*(n+1))/2;
	// int arr_sum=0;
	// int repeating=0;
	// for(int i=0; i<arr.size(); i++) {
	// 	arr_sum+=arr[i];
	// 	ans=ans^arr[i];
	// }
	// int missing_number=ans-(sum-arr_sum);
	// pair<int,int> output;
	// output.first=missing_number;
	// output.second=ans;
	// return output;
	

	// int repnum = arr[0];
	// for(int i = 1 ; i < n ; i++){
	// 	repnum = (repnum^arr[i]);
	// }
    // int extra = abs(arr_sum-repnum);
	// int p = sum-extra;
    //     pair<int, int> m = {p, repnum};
    //     return m;

}
