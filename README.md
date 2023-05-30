# Jmeter_bookingapi
Dear,

I’ve completed performance test on frequently used API for test App 

Test executed for the below mentioned scenario in server 

10 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 1.33 And Total Concurrent API requested: 80

20 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 2.67 And Total Concurrent API requested: 160.

100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 13.33 And Total Concurrent API requested: 800.

800 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 94.43 And Total Concurrent API requested: 6400

1500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 57 And Total Concurrent API requested: 12000

2500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 168.4 And Total Concurrent API requested: 20000

2800 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 261  And Total Concurrent API requested: 22400

2900 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 282 And Total Concurrent API requested: 23200

- While executed 2900 concurrent request, found 1 request got connection timeout and error rate is 0.01%.

Summary: Server can handle almost concurrent 23200  API call with almost zero (0) error rate.

Report :

![Screenshot (334)](https://github.com/Swarna2509/Jmeter_bookingapi/assets/72212832/26da3bb2-a37c-4c54-ba6e-6b608d1524f5)
![Screenshot (335)](https://github.com/Swarna2509/Jmeter_bookingapi/assets/72212832/8cfb78f8-4239-4325-b284-0cfe792d9a2a)
![Screenshot (336)](https://github.com/Swarna2509/Jmeter_bookingapi/assets/72212832/2575f5a4-0abb-4fa6-b17b-e72c9680a047)


