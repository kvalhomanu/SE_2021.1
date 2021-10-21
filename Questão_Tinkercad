// biblioteca  arduino para display
#include <LiquidCrystal.h>


LiquidCrystal lcd(7, 6, 5, 4, 3, 2);  // Pinos LCD
const int pot = 0;          // pino de entrada do potenciômetro
int tensaoPot = 0;			// variavel para armazenar valor do potenciometro

void setup() {
  lcd.begin(16, 2);					// Inicialização de LCD 16x2
  lcd.print("IFPB - SE_2021.1");      // Titulo
}

void loop() {
  lcd.setCursor(0, 1);					//Setando posição inicial do cursor no LCD
  tensaoPot = analogRead(pot);  		// recebe valor do potenciometro
  lcd.print("Tensao: ");                
  lcd.print(tensaoPot);                   // mostrando tensao no display
  delay(100);                          // tempo para nova leitura
}
