Lab #1
#include <iostream>
#include <stdio.h>
// Complete a swap() function
// Use this function to swap the values of two integers by using pointers only.
void swap(int *p1, int *p2) {
  int blya=*p1;
    *p1=*p2;
    *p2=blya;
}
int main() {
  int x = 10;
  int y = 20;
  swap(&x, &y);
  printf("x: %d, y: %d", x, y);
  return 0;
}
