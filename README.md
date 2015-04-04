# challenge-problem
# Challenge problem from career fair
// Assume this program is run on a little-endian machine. What does it print?
void main () // Begins C++ program
{
  unsigned int array[4] = {0,0,0,1025}; // Declares an array 
  
  printf("%u", *( ( (char*)&(array[3]) ) + 1) ); 
    // prints formatted data , unsigned decimal integer, 
    // * width , 
}
