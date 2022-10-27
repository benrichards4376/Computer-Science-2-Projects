# Computer-Science-2-Projects
This contains descriptions of projects I completed while taking Computer Science 2 at UCF. My instructor, Dr. Szumlanski has instructed to not share any code from his projects under threat of legal action. I have a private repository containing all the code, which I am allowed to share with potential employers, but cannot be made public for the aforementioned reason. All projects in CS2 are in Java.

SkipList: An implementation of the probablistic skip list data structure. Can contain any data that extends comparable. Supports the following methods:
Skiplist() - default size 0, default height 0
Skiplist(int height)

insert(AnyType data)
insert(int height, AnyType data)
delete(AnyType data)

get(AnyType data)
contains(AnyType data)

print_list()


SneakyQueens: Given an ArrayList of string coordinates on a chess board, in the form (L^+ D^+), convert to numerical coordinates (e.g. a3 should be converted to 1, 3), and return false if one or more of the queens can attack one another, or true otherwise.
