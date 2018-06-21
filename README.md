# Documentation Java SE 8 Stream API #
https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html

## stream() ##

List<Integer> myList = new ArrayList<Integer>();
  
Stream<Integer> myStream = myList.**stream()**;

## forEach() ##

myStream.**forEach**(e -> System.out.println(e));

