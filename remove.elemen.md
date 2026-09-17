```java

class Solution {

&#x20;   public int removeElement(int\[] nums, int val) {

&#x20;       int k = 0;



&#x20;       for (int i = 0; i < nums.length; i++) {

&#x20;           if (nums\[i] != val) {

&#x20;               nums\[k] = nums\[i];

&#x20;               k++;

&#x20;           }

&#x20;       }



&#x20;       return k;

&#x20;   }

}

```



