# bound-eles
class Solution {
public:
    vector<int> BoundaryElements(vector<vector<int>>&matrix){
        // Code here
        int n=matrix.size();
        vector<int>v;
        for(int i=0;i<n;i++){
            for(int j=0;j<n;j++){
               if(i==0 || i==n-1)
               {
                   v.push_back(matrix[i][j]);
               }
               else {
                   if(j==0 || j==n-1)
               {
                   v.push_back(matrix[i][j]);
               }
            }
        }
        }
        return v;
    }
};
