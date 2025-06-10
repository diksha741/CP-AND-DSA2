this file will save the solutions to the question that are locked on leetcode 

<div>
1874

sort(nums1.begin(),nums1.end());
sort(nums2.begin(),nums2.end(),greater<int>());
int ans = 0;
for(int i=0;i< n;i++){
    ans = ans + nums1[i] * nums2[i];
    }

return ans;
</div>

<div>
3064

int count =0;
while(n>0){
    int r = n%2;
    n = n/2;
    count++;
}
return count;
</div>

<div>
1570

not efficient
int ans =0;
for(int i=0;i< n;i++>){
    if(a[i]!=0 && b[i]!=0){
        ans = ans+a[i]*b[i];
    }
}
return ans;

efficient 
uses hashmap
</div>

<div>
