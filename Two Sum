class Solution{
  public int[] twoSum(int[] nums, int target){
    for(int i = 0; i < nums.length-1; i++){
      for(int j = i+1; j < nums.length; j++){ //dont sum with self, always check 1 more than ith position
        if(nums[i]+nums[j] == target){
          return new int[]{i,j};    //return the 2 indicies
        }
      }
    }
    return new int[]{};   //return an empty array to indicate failure
  }

}
