# praca_magisterska

## Fuzzification EURUSD_1h 
Reguły rozmycia. Przygotowane tylko dla 'NMA'.


## mgr_data_preprocess_EURUSD_1h
-'Return' - zwrot logarytmiczny 
- 'Up/Down' - sprawdza, które zwroty są dodanie/ujemne i przypisuje wartość z 'Return' do odpowiedniej kolumny
- 'avg_14up/down' - 14 dniowa 'strata' (do wyliczenia RSI)
- 'RS_14' - avg_14up/avg_14down
- 'RSI' - RSI
- '5MA', '15MA' - 5cio i 15 dniowa średnia ruchoma
- '12Ewm', '26Ewm' - 12 i 26 dniowa średnia ważona
- 'MACD' - 12Ewm - 26Ewm
- 'low_14/high_14' - 14 dniowa średnia z najniższych/najwyższych wartości
- 'k_percent' - stochastyczny oscylator
- 'B_MA, BU, BL' - 15dniowa średnia ruchoma, górna i dolna wstęga
