/*Date:     07-08-2021
By:         Maderdash
This is just a test code to test if the driver is running correctly.
We are not useing the EN pins on the controller. 
Be sure the jumpers are conected to the EN pins. Or apply 5v to both pins.

*/

int motor1pin1 = 11;
int motor1pin2 = 10;

int motor2pin1 = 9;
int motor2pin2 = 6;

void setup() {
  // put your setup code here, to run once:
  pinMode(motor1pin1, OUTPUT);
  pinMode(motor1pin2, OUTPUT);
  pinMode(motor2pin1, OUTPUT);
  pinMode(motor2pin2, OUTPUT);
  Serial.begin(9600);
}

void loop() {
  // put your main code here, to run repeatedly:   
  analogWrite(motor1pin1, 255);
  analogWrite(motor1pin2, 0);

  analogWrite(motor2pin1, 255);
  analogWrite(motor2pin2, 0);
  Serial.println("direction A is turing now.");
  delay(1000);

  analogWrite(motor1pin1, 0);
  analogWrite(motor1pin2, 255);

  analogWrite(motor2pin1, 0);
  analogWrite(motor2pin2, 255);
  Serial.println("direction A is turing now.");
  delay(1000);
}
  
