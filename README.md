class Solution {
    public int[] computeOperations(int x, int y) {
        // code here
        int p=x+y;
        int q=x-y;
        int r=x*y;
        int s=x/y;
        int t=x%y;
        return new int[]{p,q,r,s,t};
        
    }
    public static void main(String [] args){
        Solution obj = new Solution();
        int[] result = obj.computeOperations(1,2);
        System.out.println(Arrays.toString(result));
    }
}
