Linux Learning

 A. How to set user password expire in days
     chage -M 90 orbit ( Maximum )
    To check details chage -l orbit
    
    Last password change                                    : Jun 18, 2018
    Password expires                                        : Sep 16, 2018
    Password inactive                                       : never
    Account expires                                         : never
    Minimum number of days between password change          : 1
    Maximum number of days between password change          : 90
    Number of days of warning before password expires       : 7
 B. Minimum days for password change
     chage -m 1 orbit
     
     to see chage -l orbit
      
      Last password change                                    : Jun 18, 2018
      Password expires                                        : Sep 16, 2018
      Password inactive                                       : never
      Account expires                                         : never
      Minimum number of days between password change          : 0
      Maximum number of days between password change          : 90
      Number of days of warning before password expires       : 7


