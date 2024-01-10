# Computer-Science-2-Projects
This contains descriptions of projects I completed while taking Computer Science 2 at UCF. My instructor, Dr. Szumlanski has instructed to not share any code from his projects. I have a private repository containing all the code, which I am allowed to share with potential employers, but cannot be made public for the aforementioned reason. All projects in CS2 are in Java.

Pathogen: A backtracking algorithm that returns all the valid solutions to a maze, read from a file with the following legend:
<br /> Maze Legend: <br /> (X) denotes an untouchable space. <br /> (Y) denotes a touchable space. <br />

| Symbol    | Meaning   |
| :-------: | :-------- |
| #         | Wall  (X) |
| *         | Virus (X) |
| .         | Crumb (X) |
| e         | Exit  (Y) |
| @         | Start (Y) |

(Note: crumbs are left in previously visited spaces as to not allow duplicate states, they are not in the original text files) <br /> <br />
SkipList: An implementation of the probablistic skip list data structure. <br /> Can contain any data type that extends comparable. Support the following methods: <br />

| Method     | Description |
| :--------- | :---------- |
| Skiplist() | Constructs a skiplist with a default height and size of zero |
| Skiplist(int height) | Constructs a skiplist of size 0 and height set to the given height, default 0 |
| insert(AnyType data) | Generates a node height so a node of height n has a $\frac{1}{2^n}$ chance of being created. Calls insert(int height, AnyType data) |
| insert(int height, AnyType data) | Creates a node with the given height and data, and inserts it into the list |
| delete(AnyType data) | Removes the first occurence of the given data from the skiplist |
| get(AnyType data) | Returns the first node in the skiplist that contains the given data; Otherwise, returns null |
| contains(AnyType data) | Returns true if skiplist contains a node with the given data; Otherwise, returns false |
| print_list() | prints the data and height of each node, as well as what each node is pointing to at each level

IMPORTANT: insert(Anytype data) calls insert(int height, Anytype data)


SneakyQueens: Given an ArrayList of string coordinates on a chess board, in the form $(L^+ D^+)$, convert to numerical coordinates (e.g. a3 should be converted to 1, 3), and return false if one or more of the queens can attack one another, or true otherwise.
