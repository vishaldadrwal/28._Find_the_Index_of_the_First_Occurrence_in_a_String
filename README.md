# 28._Find_the_Index_of_the_First_Occurrence_in_a_String
# Given two strings needle and haystack, return the index of the first occurrence of needle in haystack, or -1 if needle is not part of haystack.
class Solution {
public:
    int strStr(string haystack, string needle) {
        return haystack.find(needle);
    }
};
