#include <MPU6050_tockn.h>
#include <Servo.h>
#include <Wire.h>
/* Cria os objetos de controle para cada servomotor. */
Servo servoX;
Servo servoY;
Servo servoZ;
int led1 = 5;
int led2 = 6;
/* Cria o objeto de controle do módulo MPU6050. */
MPU6050 mpu6050(Wire);

