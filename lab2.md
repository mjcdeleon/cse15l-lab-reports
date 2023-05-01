# Part 1




# Part 2

## A failure-inducing input

## An input that does not produce a failure

## The symptom as an output running of the tests

## The bug
### BEFORE CHANGE
`  static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = newArray[arr.length - i - 1];
    }
    return arr;
  }
`

### AFTER CHANGE
`  static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      newArray[i] = arr[arr.length - i - 1];
    }
    return newArray;
  }
`


# Part 3
Something I had learned from week 2 was about the structure of a URL and the breakdown of each component. I learned the correct terminology for all parts of the URL. Previously I had only known about the domain of a URL, after week 2 I learned about the protocol, path/part, query, and anchor/fragment.
