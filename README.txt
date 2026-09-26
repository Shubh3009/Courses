
Brute Force Method

Check every number from 1 to n.

cpp

vector<int> divisors;
for (int i = 1; i <= n; i++) {
    if (n % i == 0)
        divisors.push_back(i);
}

-> Time Complexity: O(n)
-> Works for n ≤ 10^6
-> Too slow for CP when n ≤ 10^12
