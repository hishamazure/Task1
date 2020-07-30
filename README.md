CO2 Calculaor
This program returns the amount of CO2-equivalent that will be caused when traveling between two cities using a given transportation method.
This program was created with singelton design pattern and separation of concerns concept. That is, network layer is segragated from other business layers


Getting Started
1- Copy the JAR files in the submitted task and add them to lib folder
2- Add ORS_TOKEN as environment variable and set it to your API Token
3- Have JAR file co2.jar at the same location where you want to run the command

Note: If you want to change or add more transportation means, edit the propert file in :


Prerequisites
Java 8 and above installed and in the PATH environmen variable



Running the tests
I have created some sample test and it can be found in test.TestCase1
Normally tests can be run by maven or directly in command line 
Note: Due to time constrains, I have skipped adding them to maven



To Run the application:

In command line, run:
Java -cp "co2.jar:lib/*" com.me.Tester1 --end CityName1 --start CityName2 --transportation-method trasportationMethod
Example:
Java -cp "co2.jar:lib/*" com.me.Tester1 --end Berlin --start=Hamburg --transportation-method medium-diesel-car
Java -cp "co2.jar:lib/*" com.me.Tester1 --end "New York" --start="Los Angeles"  --transportation-method medium-diesel-car




Author
Hisham Marie