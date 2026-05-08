# Simple Array Sum - HackerRank Solution (C++)

This repository contains my C++ solution for the HackerRank problem:

🔹 Simple Array Sum

## Problem Overview
Given an array of integers, calculate and return the sum of all elements in the array.

## Concepts Used
- C++
- Arrays & Vectors
- Loops
- Basic Problem Solving

## Solution
```cpp
#include <bits/stdc++.h>
using namespace std;

int simpleArraySum(vector<int> ar) {
    int sum = 0;

    for (size_t i = 0; i < ar.size(); i++) {
        sum += ar[i];
    }

    return sum;
}

int main() {
    int n;
    cin >> n;

    vector<int> ar(n);

    for (int i = 0; i < n; i++)
        cin >> ar[i];

    cout << simpleArraySum(ar);

    return 0;
}
```

## HackerRank Profile
hackerrank.com/profile/nourelsali2006
