# IDSDP_Staging_NST Fellowship _PerformanceTesting 

This performance testing was conducted on the Grant/Fellowship module IDSDP_MOST staging server using JMeter. I conducted performance testing by manually adding APIs one by one in JMeter and then performed load testing in non-GUI mode recorded with BlazeMeter.
## List of performance Testing 

- Volume Testing
- Endurance test
- Load testing for 20000 user
- Perfromnce testing of each API
## Environment 

This test was conducted using Jmeter.Blazemeter was used for the recording purpose.
## ScreenShot of some report of Performance Testing
![summary report](https://github.com/Nilufarhossain/Performance-Testing-using-Jmeter/assets/62650301/e75bff2b-7167-4800-8417-5cb679880ba3)
![aggregate report](https://github.com/Nilufarhossain/Performance-Testing-using-Jmeter/assets/62650301/fb841e3f-97f6-43b6-8e63-5c53c887e356)
## Screenshots of Load Testing HTML report
![400](https://github.com/Nilufarhossain/Performance-Testing-using-Jmeter/assets/62650301/518b45eb-db52-4f47-bb73-bdebcda84940)
![500](https://github.com/Nilufarhossain/Performance-Testing-using-Jmeter/assets/62650301/726893f0-c42e-4222-97e1-03ee14e715a4)
## Report of Load Testing

 Test executed for the below mentioned scenario in server https://tr-grant.most.gov.bd/

 -200 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 550 And Total Concurrent API requested: 8000.
 
 -300 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 750 And Total Concurrent API requested: 12000
 
 -400 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 1130 And Total Concurrent API requested: 16000.
 
 - 500 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 443 And Total Concurrent API requested: 20000.

 While executed 500 concurrent request, 7 request got internal server error and error rate is 0.04%. 

Summary: Server can handle almost concurrent 18000 API call with almost zero (0) error rate.
The Grant/Fellowship module was the first module I tested in my professional life. After successfully testing and deploying it, the module went live and was functioning perfectly. However, on the last day of the NST fellowship application, the server started to go down due to heavy user traffic. It was so slow that we were unable to work on it and the team lead had to request an extension of the deadline. This experience taught me the importance of load testing before deployment to prevent similar issues in the future.


