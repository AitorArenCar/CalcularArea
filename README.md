# README

This is a simple Java project that demonstrates the usage of the `Circulo` class.

## Project Structure

The project consists of two files:

- `Test.java` in the `figuras` package: It contains the `main` method to run the program and test the `Circulo` class.
- `Circulo.java` in the `utilidades` package: It defines the `Circulo` class, representing a circle and providing basic operations.

## Usage

To use the `Circulo` class in your own project, follow these steps:

1. Copy the `Circulo.java` file into your project's `utilidades` package.

2. Import the `Circulo` class in your code:
   ```java
   import utilidades.Circulo;
   ```

3. Create an instance of the `Circulo` class and provide the radius as a parameter:
   ```java
   Circulo c = new Circulo(radius);
   ```

4. Use the available methods of the `Circulo` class to perform operations on the circle object.

## Functionality

The `Circulo` class has the following features:

- **Constructor**: Creates a circle object with the given radius.
  ```java
  public Circulo(double radio)
  ```

- **imprimir()**: Prints the diameter, color, and area of the circle.
  ```java
  public void imprimir()
  ```

- **esIgual(Circulo otro, boolean conDecimales)**: Checks if the current circle is equal to the given circle, considering the decimal places based on the value of the `conDecimales` parameter.
  ```java
  public boolean esIgual(Circulo otro, boolean conDecimales)
  ```

Feel free to explore and use the `Circulo` class according to your needs.

Note: Remember to include the necessary import statements and package declarations in your code to access the `Circulo` class correctly.
