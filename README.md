# Speech-To-Text
A speech to text website using JavaScript , html & css
# Simple Speech to text website that supports two languages:
## English
## Arabic
# wasdom-ESP32
i'm going to write algorithm for running wasdom ESP32. So here i'm going to apply some steps to run wasdom ESP32 with Arduino.
# FlowChart
![image](https://user-images.githubusercontent.com/108229185/181574193-dbaf9e01-f498-4989-a794-73b617ee6e9a.png)
# Steps
First step
you need to download Arduino IDE by https://www.arduino.cc/en/software
Second step
now since the wasdom ESP32 is undefined so you need to define it with Arduino by clicking on file > preferences

![image](https://user-images.githubusercontent.com/108229185/181574487-efdb9794-3c19-4aaa-b11c-09aa0b866736.png)

now in Additional Boards Manager URLs put this URL then press OK .
![image](https://user-images.githubusercontent.com/108229185/181574548-d52a823f-0b69-487c-b60e-f4d1bdb3b538.png)
now move to Tools > Board: "Arduino uno" > Boards manager , maybe board option has a diffrent name but thats okay.
![image](https://user-images.githubusercontent.com/108229185/181574603-d12b264e-a345-4985-ae76-b16e02525efa.png)
then you will get a window, type in the search bar "ESP32" then press install
![image](https://user-images.githubusercontent.com/108229185/181574627-3dc46ac5-37d7-45a0-a491-73f7346be6d8.png)
now after these steps when you go to Tools > Board: "Arduino uno" you should find ESP32 Arduino.
![image](https://user-images.githubusercontent.com/108229185/181574682-2d77f128-c8d1-4736-8fdf-3fb2884ac45a.png)
# Third step
now connect wasdom ESP32 with your computer, then go and choose wemos D1 mini ESP32
![image](https://user-images.githubusercontent.com/108229185/181574745-4e0dab3a-d833-40ff-b5b2-1433dc7320db.png)
hen connect it by clicking on:
![image](https://user-images.githubusercontent.com/108229185/181574767-f35351d5-0573-4307-aad5-432555a0a863.png)
# Fourth step
now we want to make sure that everything is working so we are going to make the LED turn on and off Blink. by going to file > examples > Basics > Blink.
![image](https://user-images.githubusercontent.com/108229185/181574819-3827bc97-5382-4f3f-a267-0d225d58bf5c.png)
after that run it then we are done
