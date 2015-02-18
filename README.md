# OOPExamples
This is to show examples of object oriented programming
This will have the following languages implement the same tree object:
*Java
*Python
*C++
Java:
class Tree {
    int numberOfFruit = 0;
    int numberOfLeaves = 0;
    int branchNumber = 8;
    void changeFruitNumber(int newValue) {
         numberOfFruit = newValue;
    }
    void changeLeaves(int newValue) {
         numberOfLeaves = newValue;
    }
    void changeBranch(int increment) {
         branchNumber = newValue;   
    }
    void printStates() {
         System.out.println("How many fruits it contains:" +
             numberOfFruit + " How many leaves it contains:" + 
             numberOfLeaves + " How many branches it has:" + branchNumber);
    }
    Tree appleTree = new Tree(60,60,60);
}

Python:
class Tree:
   'Optional class documentation string'
   def __init__(self, name, numberOfFruit):
      self.name = name
      self.numberOfFruit = numberOfFruit
      
   
   def displayFruitCount(self):
     print "Total Tree %d" % Tree.numberofFruit

   def displayName(self):
      print "Name : ", self.name,  "
appleTree = Tree("Apple", 2500)

C++:
class Tree {   // classname
private:
   int numberOfFruit;         // Data members (variables)
   string name;
   int numberOfBranches;
public:   
   void countFruit(numberOfFruit);         // Member functions
   void treeName(name);
}
