[한국어](https://github.com/FTIndustries/chargemaster-1500/blob/main/readme-ko.md)
# chargemaster-1500
![preview](https://github.com/FTIndustries/chargemaster-1500/blob/main/3dpreview.png?raw=true)\
Lithium ion/polymer battery charging module based on BQ24073. It can charge batteries at up to 1500mA speed. Provides overcharge protection, power path control, selectable max charging currnet. It can draw current from battery even while charging so you don't need to worry about low current situation.
## selecting max charging current
![backpreview](https://github.com/FTIndustries/chargemaster-1500/blob/main/pcbbackpreview.png?raw=true)\
Maximum charging current is set to 1.5A by default. You can reduce it to 750mA by cutting the jumper on the back of the module. To set the current to 1.5A again, solder the jumper.
## warning about charging current
Do not charge the battery exeeding your battery's spec. The battery will be overheated and damaged, and possibly catch on fire. if your battery allows 0.5C charge rate and has capacity of 2000mAh, then maximum charging current is 1000mA. (2000*0.5)
## connector
it accepts MOLEX 51021 RB type connector. always check the polarity before connecting.\
![adsf](https://github.com/FTIndustries/chargemaster-500/assets/47267045/8cbb29fd-9ee4-4e2c-87f2-7d67e7da962e)
### protection
unlike generic TP4056 module, this module does not provide overcurrent protection and overdischarge protection. you need to use protected battery pack or add external protection board.
