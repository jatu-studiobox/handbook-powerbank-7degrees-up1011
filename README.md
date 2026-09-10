# Handbook Powerbank 7degrees Model UP1011 Thai/EN Language

## วิธีใช้งาน powerbank 7 degrees UP1011

### วิธีการชาร์จอุปกรณ์ (มือถือหรือแท็บเล็ต)
* นำสายชาร์จ USB เสียบเข้ากับช่องพอร์ตจ่ายไฟออก (USB Output) ของพาวเวอร์แบงค์
* เสียบปลายสายอีกด้านเข้ากับสมาร์ทโฟนหรืออุปกรณ์ที่ต้องการชาร์จ
* กดปุ่มเปิด (Power) ด้านข้างตัวเครื่อง 1 ครั้ง (หากไม่มีระบบเปิดอัตโนมัติ) เพื่อเริ่มจ่ายกระแสไฟ 5V 2A
* เมื่อชาร์จเสร็จแล้ว ให้ถอดสายออกได้ทันที


#### Description

* No. `1` : Title - Thermometer's title
* No. `2` : Top Area Color - Thermometer's mercury color at top area
* No. `3` : Middle Area Color - Thermometer's mercury color at middle area
* No. `4` : Bottom Area Color - Thermometer's mercury color at bottom area
* No. `5` : Min. Temperature - Mininum temperature of thermometer for display
* No. `6` : Max. Temperature - Maxinum temperature of thermometer for display
* No. `7` : Unit - Unit for display, includes °C and °F
* No. `8` : Scale - Thermometer size for display, includes 'normal' and 'small'
* No. `9` : Number of colors - Able to choose number of color(s) for display on mercury, 1-3 color(s)
* No. `10` : Decimal(s) of Temp. - Able to use temperature value with decimal(s) for display, 0-3 decimal(s)
* No. `11` : Display level % - Able to set display level percentage (Hide/Show).
* No. `12` : Current Temp. Size - Able to set current temperature font size for display (1.2 to 3.2 step 0.2).

### API Input
Using `msg` object.

| Property     | Mandatory   | Type      | Description |
| ------------ |:-----------:|:---------:| ----------- |
| payload      | Yes         | `Number` | Temperature value for display on thermometer |
