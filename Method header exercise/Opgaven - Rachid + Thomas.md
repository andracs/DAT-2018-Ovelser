# Method header exercise

La’ os øve os på at skrive metode-headers. Klassen hedder Smartsensor. Skrive metode headers (eller hele metoder),
- som læser den nuværende temperatur ud i Celsius	//public double readTempCels(){return tempCels;}
- som læser den nuværende temperatur ud i Kelvin	//public double readTempKel(){return tempKel;}
- som returnerer de sidste 5 temperaturer,		//public double[] readTempLastFive(){return temp[];}
- som returnerer de sidste x temperaturer		//public double[] readTempLastFive(int x){return temp[];}	
- som returnerer 
- som genstarter måleren				//public void restartSensor(){}
- som sender en Opdateringsobjekt til måleren		//public boolean updateSensor(UpdateObject update){boolean success; return success }
- som modtager en kanalnummer (int) for kommunikation	//public void newChannel(int channelNumber){}
- constructoren skal tage imod smartsensorens IP-nummer eller serienummer (int), eller begge dele.	// public SmartSensor(String ipAddress){}
													// public SmartSensor(String serialNumber){}
													// public SmartSensor(String ipAddress, String serialNumber){}
