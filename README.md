# motor-automation
 #define BLYNK_TEMPLATE_ID "TMPL8FpjjgGR"
#define BLYNK_DEVICE_NAME "Quickstart Template"
#define BLYNK_AUTH_TOKEN "NQd-Aj1aqvVfCKHRFpn_a5-b5RiarhaD"
  #define BLYNK_PRINT Serial
  #include <ESP8266WiFi.h>
  #include<BlynkSimpleEsp8266.h>
  int ledPin = 13;
  int buttonPin = 4;

  char auth[]="NQd-Aj1aqvVfCKHRFpn_a5-b5RiarhaD";
  char ssid[]="kamal";
  char pass[]="Hello";
void setup() {
  // put your setup code here, to run once:
   pinMode(ledPin, OUTPUT);
  Serial.begin(9600);
  Blynk.begin(NQd-Aj1aqvVfCKHRFpn_a5-b5RiarhaD,kamal,Hello);
  Blynk.syncAll();

}

void loop() {
  // put your main code here, to run repeatedly:
  Blynk.run();
}
