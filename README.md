# Vaja1-ADC-single-conversion-STM32F0

ODGOVORI: 
2. b) PC0 
   c) 1 ADC pretvornik 
   d) Da je določeni pin že zaseden; Odpravimo napako tako da obkljukamo željeni pin v ADC zavihku… npr. IN10=PC0 
   e) 16 ADC + 2 Druga 
   f) ADC_IN10 
   h) a.   12-Bit, 0-4095
      b.   6-Bit, 0-63
      c.   10-Bit, 0-1023

Komentar: V Configuration -> ADC -> imamo izbrano 12-bitno (0 do 4095) ločljivost pretvorbe namesto 8-bitne (od 0 do 255).
