int missingNumber(int arr[], int n)
{
 int fr[n+1] = {0};
 for(int i = 0; i<n; i++){
     int index = arr[i];
     fr[index]++;
 }
 for(int i = 0; i< n+1; i++) {
     if(fr[i] == 0)
     return i;
 }   
}
