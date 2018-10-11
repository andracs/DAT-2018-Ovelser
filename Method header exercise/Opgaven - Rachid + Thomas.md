# Method header exercise

La’ os øve os på at skrive metode-headers. Klassen hedder Smartsensor. Skrive metode headers (eller hele metoder),
- som læser den nuværende temperatur ud i Celsius	\n
//public double readTempCels(){return tempCels;}\n
- som læser den nuværende temperatur ud i Kelvin	\n
//public double readTempKel(){return tempKel;}\n
- som returnerer de sidste 5 temperaturer,		\n
//public double[] readTempLastFive(){return temp[];}\n
- som returnerer de sidste x temperaturer		\n
//public double[] readTempLastFive(int x){return temp[];}	\n
- som returnerer \n
- som genstarter måleren				\n
//public void restartSensor(){}\n
- som sender en Opdateringsobjekt til måleren		\n
//public boolean updateSensor(UpdateObject update){boolean success; return success }\n
- som modtager en kanalnummer (int) for kommunikation	\n
//public void newChannel(int channelNumber){}\n
- constructoren skal tage imod smartsensorens IP-nummer eller serienummer (int), eller begge dele.	\n
// public SmartSensor(String ipAddress){}\n
// public SmartSensor(int serialNumber){}\n
// public SmartSensor(String ipAddress, int serialNumber){}\n
