ມິໂຄຣໂປຣເຊສເຊີ (Microprocessor) ແລະ ມິໂຄຣຄອນໂທລເລີ (Microcontroller) ແມ່ນຊິບ “ສະໝອງ” ຂອງອຸປະກອນໄຟຟ້າ/ຄອມພິວເຕີ, ແຕ່ຈຸດປະສົງແລະການນໍາໃຊ້ບໍ່ເໝາະກັນ:

### Microprocessor :

- ແມ່ນຊິບທີ່ມີ **CPU ຢ່າງດຽວ** (ໂຕປະມວນຜົນການຄໍານວນ).
- ຈະໃຊ້ງານໄດ້ຕ້ອງພຶງ **RAM, ROM/Storage, I/O** ພາຍນອກເພີ່ມ.
- ເໝາະກັບງານທົ່ວໄປທີ່ຊັບຊ້ອນ/ປະສິດທິພາບສູງ: ເຊັ່ນ laptop, desktop, server.
- ຕົວຢ່າງ: Intel Core, AMD Ryzen, ARM Cortex-A.
### Microcontroller :

- ແມ່ນຊິບທີ່ **ລວມທຸກຢ່າງໃນອັນດຽວ**: CPU + RAM + Flash/ROM + I/O (GPIO, UART, I²C, SPI) ແລະບາງທີ່ມີ ADC/DAC, Timer.
- ອອກແບບເພື່ອ **ວຽກສະເພາະ** ໃນລະບົບຝັງຕົວ (embedded) ໃຊ້ໄຟນ້ອຍ ແລະ ຕົ້ນທຶນຕໍ່ໍ່ໍ່ໍຕໍ່ໍຕ່ໍາ.
- ຕົວຢ່າງ: Arduino/AVR, PIC, STM32 (ARM Cortex-M), ESP32/ESP8266.

### ຄວາມແຕກຕ່າງຫຼັກໆ 

- **ສ່ວນປະກອບ**:

- Microprocessor: ມີ CPU ຢ່າງດຽວ → ຕ້ອງຕໍ່ອຸປະກອນພາຍນອກ 
- Microcontroller: ມີທຸກຢ່າງຢູ່ໃນຊິບ → ຕໍ່ໄດ້ເລີຍ, ພ້ອມໃຊ້.

- **ຈຸດປະສົງ**:

- Microprocessor: ວຽກຫນັກ, ຫຼາຍໜ້າທີ່, ຮັນ OS ເຕັມ (Windows, Linux).
- Microcontroller: ວຽກຈຸດດຽວ/ສະເພາະ ເຊັ່ນ ຄວບຄຸມມໍເຕີ, ອ່ານ sensor.

- **ພະລັງງານ & ລາຄາ**:

- Microprocessor: ກິນໄຟຫຼາຍ, ແພງກວ່າ.
- Microcontroller: ປະຫຍັດໄຟ, ຖືກ, ເຫມາະກັບ IoT/ອຸປະກອນພົກພາ.

- **ຄວາມໄວ/ປະສິດທິພາບ**:

- Microprocessor: ຄຳນວນແຮງ, ຮອງຮັບແອັບຊັບຊ້ອນ.
- Microcontroller: ໄວພໍງານຄວບຄຸມ, ແຕ່ບໍ່ໄດ້ອອກແບບເພື່ອງານໜັກ.


### ໃນການເຮັດວຽກ

- **Microprocessor**: ຮັນ OS → OS ຈັດການແອັບ, ໜ່ວຍຄວາມຈໍາ, ເຄືອຂ່າຍ. CPU ປະມວນຄໍາສັ່ງຈາກແອັບ/OS ຜ່ານ RAM ແລະ I/O ພາຍນອກ.

- **Microcontroller**: ໂປຣແກຣມ (firmware) ຖືກເກັບໃນ Flash ຂອງຊິບ → ເວລາເປີດໄຟຈະຮັນ loop ຄວບຄຸມ I/O (ອ່ານ sensor, ສັ່ງ motor/LED) ໂດຍກົງ ແລະກິນໄຟນ້ອຍ.



