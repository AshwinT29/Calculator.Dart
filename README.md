# Calculator.Dart
class Mathematics {
  int addition(int a, int b) {
    return a + b;
  }

  int subtraction(int a, int b) {
    return a - b;
  }

  int multiplication(int a, int b) {
    return a * b;
  }

  double division(int a, int b) {
    return a / b;
  }
}

void main() {
  Mathematics math = new Mathematics();
  int a = 72;
  int b = 15;

  int addResult = math.addition(a, b);
  print(addResult);
  int subResult = math.subtraction(a, b);
  print(subResult);
  int mulResult = math.multiplication(a, b);
  print(mulResult);
  double divResult = math.division(a, b);
  print(divResult);
}
Footer
© 2025 GitHub, Inc.
Footer navigation
Terms
P
