# How to contribute ?

1.	Search about the the topic or domain on which you want to  contribute like course topic, provided by, platform, etc.
2.	Take the reference from below example and structure your  information similar to that .
3.	Check your code.
4.	Commit your change and go for pull request.
NOTE-Wrong syntax code can be rejected.
NOTE1 - Contribution must be done in the given format. Pull request wont be accepted if the format is wrong.
# Example



 {
      
      "id":"1",
      
      "topic":"DSA - Array",
      
      "question":"Find pair with given sum in the array",
      
      "answer_link":"// C++ program for the above approach
#include <bits/stdc++.h>
 
using namespace std;
 
// Function to find and print pair
bool chkPair(int A[], int size, int x)
{
    for (int i = 0; i < (size - 1); i++) {
        for (int j = (i + 1); j < size; j++) {
            if (A[i] + A[j] == x) {
                return 1;
            }
        }
    }
 
    return 0;
}"
 }



