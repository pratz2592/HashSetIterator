# HashSetIterator

import java.util.HashSet;

import java.util.Iterator;

public class HashSetIterator {

  public static void main(String[] args) {
  
    HashSet hashSet = new HashSet();

    hashSet.add("element_1");
    hashSet.add("element_2");

    hashSet.add("element_3");

    // Iterator use the iterator() operation

    Iterator it = hashSet.iterator();
    System.out.println("Elements in HashSet :");
    while(it.hasNext())

 

System.out.println(it.next());

  }

}
