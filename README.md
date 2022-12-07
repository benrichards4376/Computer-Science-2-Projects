# Computer-Science-2-Projects
This contains descriptions of projects I completed while taking Computer Science 2 at UCF. My instructor, Dr. Szumlanski has instructed to not share any code from his projects under threat of legal action. I have a private repository containing all the code, which I am allowed to share with potential employers, but cannot be made public for the aforementioned reason. All projects in CS2 are in Java.

SkipList: An implementation of the probablistic skip list data structure. Can contain any data type that extends comparable. Supports two constructors:<br /> <br />
  >Skiplist() - default size 0, default height 0 <br /> 
  >Skiplist(int height) - default size 1, default height set to parameter "height"<br />

  Supports the following methods: 
  ><br />(IMPORTANT: insert(Anytype data) calls insert(int height, Anytype data))<br /> <br />
  >insert(AnyType data) - Inserts the given data at a height probablistically generated such that a node of height n has a $\frac{1}{2^n}$ chance of being chosen. <br />    <br />
  >insert(int height, AnyType data) - Inserts the given data into a node of the given height. <br /> <br />
  >delete(AnyType data) - Removes the first occurence of the given data from the skiplist <br /> <br />
  >get(AnyType data) - Returns the first occurence of the given data in the skiplist. Otherwise, returns null. <br /> <br />
  >contains(AnyType data) - Returns true if the given data is contained in the skiplist, returns false otherwise. <br /> <br />
  >print_list()- prints the data and height of each node, as well as what each node is pointing to at each level. <br /> <br />

SneakyQueens: Given an ArrayList of string coordinates on a chess board, in the form (L^+ D^+), convert to numerical coordinates (e.g. a3 should be converted to 1, 3), and return false if one or more of the queens can attack one another, or true otherwise.
