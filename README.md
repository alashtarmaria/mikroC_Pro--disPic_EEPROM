# mikroC_Pro--disPic_EEPROM

 ### **Açıklama (Description):**  
Bu program, **I2C kütüphane fonksiyonlarının kullanımını** göstermektedir.  
Program, **I2C veri yolu üzerinden 24C02 EEPROM çipi ile haberleşme sağlar,** belirli bir konuma **bir byte veri yazar**, ardından **bu veriyi okuyarak PORTB üzerine yansıtır.**  

---

### **Test Konfigürasyonu (Test configuration):**  

- **Mikrodenetleyici (MCU):**  
  **P33EP512MU810**  

- **Geliştirme Kartı (Dev. Board):**  
  **EasyPIC Fusion v7 - Seri EEPROM modülü ile**  

- **Osilatör (Oscillator):**  
  **XT-PLL, 140.0000 MHz**  


---

### **Notlar (NOTES):**  

🔹 **Kart ayarları:**  

✅ **I2C hatlarını açın**  
➡ **SW14.3 (RA2) ve SW14.4 (RA3) anahtarlarını açın.**  

✅ **PORTA üzerindeki LED'leri kapatın**  
➡ **SW15.1 anahtarını kapatın.** 

✅ **PORTB ve PORTD üzerindeki LED'leri açın, PORTA LED'lerini kapatın**  
➡ **SW15.1 anahtarını kapatın.** 
