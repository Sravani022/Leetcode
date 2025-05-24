# valid anagram problem
class Solution {
    public boolean isAnagram(String s, String t) {
        if (s.length() != t.length()) {
            return false;
        }
        
        int[] freq = new int[26];
        for (int i = 0; i < s.length(); i++) {
            freq[s.charAt(i) - 'a']++;
            freq[t.charAt(i) - 'a']--;
        }
        
        for (int i = 0; i < freq.length; i++) {
            if (freq[i] != 0) {
                return false;
            }
        }
        
        return true;
    }
}

# Bulb Switcher
class Solution {
    public int bulbSwitch(int n) {
        
    }
}

# Heater
class Solution {
    public int findRadius(int[] houses, int[] heaters) {
        
    }
}

# Can I Win
class Solution {
    public boolean canIWin(int maxChoosableInteger, int desiredTotal) {
        
    }
}

# Water and Jug Problem
class Solution {
    public boolean canMeasureWater(int x, int y, int target) {
        
    }
}

# Find the Peaks
class Solution {
    public List<Integer> findPeaks(int[] mountain) {
        
    }
}

# House Robber
class Solution {
    public int rob(int[] nums) {
        
    }
}

# Pass the Pillow
class Solution {
    public int passThePillow(int n, int time) {
        
    }
}

# Time Needed to Buy Tickets
class Solution {
    public int timeRequiredToBuy(int[] tickets, int k) {
        
    }
}

# Calculate Money in Leetcode Bank
class Solution {
    public int totalMoney(int n) {
        
    }
}

# Hamming Distance
class Solution {
    public int hammingDistance(int x, int y) {
        
    }
}

 # Predict the Winner
class Solution {
    public boolean predictTheWinner(int[] nums) {
        
    }
}

# Palindrome Number
class Solution {
    public boolean isPalindrome(int x) {
        
    }
}

# Count Good Numbers
class Solution {
    public int countGoodNumbers(long n) {
        
    }
}

# Single Number
class Solution {
    public int singleNumber(int[] nums) {
        
    }
}

# Plus One
class Solution {
    public int[] plusOne(int[] digits) {
        
    }
}

# Arranging Coins
class Solution {
    public int arrangeCoins(int n) {
        
    }
}

# Distribute Candies to People
class Solution {
    public int[] distributeCandies(int candies, int num_people) {
        
    }
}

# Find Numbers With Even Number of digit
class Solution {
    public int findNumbers(int[] nums) {
        
    }
}


# Rings And Rods
class Solution {
    public int countPoints(String rings) {
        
    }
}

# Bulls and Cows
class Solution {
    public String getHint(String secret, String guess) {
        
    }
}

# Poor Pigs
class Solution {
    public int poorPigs(int buckets, int minutesToDie, int minutesToTest) {
        
    }
}

# Best Poker Hand
class Solution {
    public String bestHand(int[] ranks, char[] suits) {
        
    }
}
