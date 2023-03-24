# JoConnectMySQL
java connect database mysql
# ວິທີການຕິດຕັ້ງ
1. ຄິກຂວາໃສ່ **Libraries > Add JAR/Floder**
2. ເລືອກເອົາໄຟ **JoConnectMySQL.jar**
3. ເລືອກເອົາໄຟໃນໂຟເດີ lib > **mysql-connector-j-8.0.31.jar** ແລະ **mysql-connector.jar**
***
# ວິທີການໃຊ້ງານ
1.ນຳເຂົ້າຄຳສັງ

`import java.sql.*`

2.ໃຊ້ງານ Class JoConnectMySQL

`JoConnentMySQL jocon = new JoConnentMySQL("localhost", "YourServerUser", "YourPassword", "YourDatabase");`

- localhost : ທີ່ຢູ່ຂອງເຄື່ອງ
- YourServerUser : ຊື່ຜູ້ໃຊ້ງານຂອງຖານຂໍ້ມູນ
- YourPassword : ລະຫັດຜ່ານ
- YourDatabase : ຊື່ຂອງຖານຂໍ້ມູນ

### ຕົວຢ່າງ

`JoConnentMySQL jocon = new JoConnentMySQL("localhost", "root", "1234", "db_myschool");`
