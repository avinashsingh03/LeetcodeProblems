class Solution {
public:
    int matchPlayersAndTrainers(vector<int>& players, vector<int>& trainers) {
        sort(players.begin(), players.end());
        sort(trainers.begin(), trainers.end());
        int i = players.size() - 1, j = trainers.size() - 1, res = 0;
        while (i >= 0 && j >= 0) {
            if (players[i] <= trainers[j]) {
                res++;
                j--;
            }
            i--;
        }
        return res;
    }
};
