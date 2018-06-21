# Documentation Java SE 8 Stream API #
https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html

## stream() ##

List<Integer> myList = new ArrayList<Integer>();
  
Stream<Integer> myStream = myList.**stream()**;

## forEach() ##

myStream.**forEach**(e -> System.out.println(e));


## map() ##

String[] myArray = new String[]{"bob", "alice", "paul", "ellie"};

Stream<String> myStream = Arrays.stream(myArray);

Stream<String> myNewStream = myStream.**map**(s -> s.toUpperCase());

## filter() ##

String[] myArray = new String[]{"bob", "alice", "paul", "ellie"};

String[] myNewArray = Arrays.stream(myArray)

   .**filter**(s -> s.length() > 4)
          
   .**toArray**(String[]::new);
  
  
