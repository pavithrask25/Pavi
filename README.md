# Pavi
1) First sort jobs according to finish time.
2) Now apply following recursive process. 
   // Here arr[] is array of n jobs
   findMaximumProfit(arr[], n)
   {
     a) if (n == 1) return arr[0];
     b) Return the maximum of following two profits.
         (i) Maximum profit by excluding current job, i.e., 
             findMaximumProfit(arr, n-1)
         (ii) Maximum profit by including the current job            
   }
