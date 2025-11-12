class Solution {
public:
    int minOperations(vector<int>& nums) {
        int gcd = nums[0];
        for (int i = 0; i < nums.size(); i++) {
            if (nums[i] == 1) {
                int ans = 0;
                for (int x : nums) {
                    if (x != 1) ans++;
                }
                return ans;
            }
            if (i < nums.size() - 1)
                gcd = __gcd(gcd, nums[i + 1]);
        }

        if (gcd != 1) return -1;

        int ans = 1e9;
        for (int i = 0; i < nums.size(); i++) {
            int g = nums[i];
            for (int j = i + 1; j < nums.size(); j++) {
                g = __gcd(g, nums[j]);
                if (g == 1) {
                    ans = min(ans, j - i - 1 + (int)nums.size());
                    break;
                }
            }
        }
        return ans;
    }
};
