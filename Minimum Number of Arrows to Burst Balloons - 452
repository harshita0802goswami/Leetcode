class Solution {
    public int findMinArrowShots(int[][] points) {
        Arrays.sort(points, (x,y) ->Integer.compare(x[1],y[1]));
        
        int ans = 1;
        int pos = points[0][1];
        
        for(int i =0;i<points.length;i++){
            if(points[i][0] > pos){
                ans++;
                pos = points[i][1];
            }
        }
        return ans;
    }
}
