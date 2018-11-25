# SignalResearch-in-Bitcoin
SignalResearch in Bitcoin: Successful reading of btcusdt:binance data; Call alpha101, alpha191, Technical factor and Custom factor; Write a research report.; 
# 1.Successfully read the btcusdt:binance data, drawing 30Min and 1H gap map
* 'start_date':20180601000000
# 2.Call the alpha10 in the alpha101research to draw the charts, define events and print performance.
* 1.draw out the alpha10_dv30M_ma5_ma20、alpha10_dv1H_ma5_ma20 map
* 2.define alpha10's golden fork & dead fork events with cycles of 20 and 55, and print out Long_short performance
define alpha10's signal
```
for dvAdd in [dv30M, dv1H]:
    dvAdd.add_formula('alpha10_C','If(Ts_Min(Delta(close,1),4)>0,Delta(close,1),If((Ts_Max(Delta(close,1),4)<0),Delta(close,1),(-1*Delta(close,1))))',add_data=True)
```
# 3.Print out the time point of the Morningstar event and draw a picture of Morningstar and volume
* 'symbol': 'BTCUSDT:binance'
* 'freq': '1H','start_date':20180601000000
# 4.Signal Research
* call alpha101, alpha191, technical factors, candleresearch or custom derivative factors
* paint observation chart 
* write research reports(draw what factors, think about what phenomenon, describe the phenomenon)
# 5.Separately complete the signal hypothesis of two factors
# 6.Implement one of the assumptions.
