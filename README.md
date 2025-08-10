# DolphinTracking

The idea is to make an ultrasound based Tracking system to be as low cost as posible and as accurate as possible.

Current available technology does not provide accurate enuogh or to expensive 6dof tracking to be usefull for vr.

I think it is possible to create a mm accurate tracking system for vr using ultrasound combined with some clever techniques.

## Ideas

Using infrared together with sound and comparing the delay.
This method is inspired by the phenomena that you can see a lighting before you can hear it and by counting the seconds between those you can calculate the distance.

Infrared is just one idea. Every timer I mention infrared it could also be any other methods of transmitting a signal like a wire or rf.

Use diffrent frequencies to allow seperation of signals. Also change frequency over time to allow a design that is low latency. SO instead of using pulses we send a continius changing signal and use that instead.

Use existing hardware to keep cost down by combining the infared sensor with the microphone sensort and parse it in one singal or stereo adc. This way this method can be used my normal operating systems without realtime requirement.

Maybe use more speakers instead of infrared to allow a design that does not even need special hardware and can be used by any phone.

Modulate information with am or fm onto sound and infrared signals

Combine method with imu for better accuracy

## Plan

I will be testing multiple metrhods and decide which is the best going forward.

For any progress or questions please join the discord server I made for this purpose.
https://discord.gg/m6Ew5UtkmC

Any help is welcome. So feel free to join the dc.

My username on discord is mh48 so feel free to write me a pm if link doesn't work.
