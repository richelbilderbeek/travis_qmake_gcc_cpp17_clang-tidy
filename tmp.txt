#include <cassert>
#include <iostream>
int f() {
  std::cout << "Hello";
  std::cout << "Hello";
  std::cout << "Hello";
  std::cout << "Hello";
  std::cout << "Hello";
}

int main() {
  static_assert(1 + 1 == 2); // C++17
#ifdef NDEBUG
#error Must use scan-build in debug mode
#endif
  int a[3] = {0, 1, 2};
  a[4] = 0;         // Access violation!
  std::cout << a[4] // Access violation!
      ;
}
