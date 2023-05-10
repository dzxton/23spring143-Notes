**Queue**
> implementation 
```java
Queue<Integer> name = new ConcurrentLinkedQueue<>()
```
**Recursion**
- a function that calls itself
> why? 
- problem using as complex data structure 
- problem of recurring nature
- always need a stopping/exiting condition
> example
```java

```
**Binary Search**
```java
private static int binarySearch(int[] data, int target, int start, int end) {
        if (start > end) {
            return -1;
        }
        int mid = data.length - 1;
        if (data[mid] == target) {
            return mid;
        }
        
        if (target > data[mid]) {
            binarySearch(data, target, mid + 1, end);
        } else {
            return binarySearch(data, target, start, end - 1);
        }
        return -1;
    }
```
