## Simple Weather Report ##

This Java project demonstrates how to create a simple weather report based on the temperature. The program uses if, else if, and else statements to classify the weather into several categories based on the temperature value.

## Features ##
Evaluates the temperature and provides a weather report.
Categories include: very cold, cold, warm, hot, and very hot.
Example ranges:
Very cold: Below -10°C
Cold: -10°C to 0°C
Warm: 0°C to 20°C
Hot: 20°C to 30°C
Very hot: Above 30°C

## Code Overview ##
The temperature variable can be modified to test different weather conditions.
Uses conditional statements to print appropriate weather messages based on the temperature.
## Example ##

```public class Main { public static void main(String[] args) { int temperature = 20; // You can change this value. if(temperature < -10) { System.out.println("The weather is very cold."); } else if (temperature >= -10 && temperature < 0) { System.out.println("The weather is cold."); } else if (temperature >= 0 && temperature <= 20) { System.out.println("The weather is warm."); } else if (temperature > 20 && temperature <= 30) { System.out.println("The weather is hot."); } else { System.out.println("The weather is very hot."); } } }```

## Usage ##
Change the temperature variable to test different weather conditions and see how the program responds.

## Additional Information ##
This example is a straightforward illustration of using conditional statements in Java. It helps in understanding how to use if, else if, and else to handle different scenarios.

## Follow Me ##
If you found this project helpful and would like to stay updated with my latest work, feel free to follow me on social media:

GitHub: github.com/uygarcode
LinkedIn: linkedin.com/in/uygarkaan
Instagram: instagram.com/uygarcode
Thank you for your support!
