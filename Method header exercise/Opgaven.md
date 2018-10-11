Method header exercise
La’ os øve os på at skrive metode-headers. Klassen hedder Smartsensor. Skrive metode headers (eller hele metoder),
som læser den nuværende temperatur ud i Celsius
           public int readCurrentTempCelcius()
som læser den nuværende temperatur ud i Kelvin
public int readCurrentTempKelvin()
som returnerer de sidste 5 temperaturer,
public int returnLastFiveTemp(int 5)
som returnerer de sidste x temperaturer
public int returnXTemp (int x)
som returnerer hvad
som genstarter måleren
public void restartMeter()
som sender en Opdateringsobjekt til måleren
public void sendUpdate(File updatefile)
som modtager en kanalnummer (int) for kommunikation
public void changeNumber(int channelNumber) 
constructoren skal tage imod smartsensorens IP-nummer eller serienummer (int), eller begge dele.
public void recieveSmartSensor(int a,int b)
