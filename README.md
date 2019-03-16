# EVchargepoints
A few scripts to monitor usage status of public EV chargepoints

#### cyc-status - shows status of a selected ChargeYourCar chargepoint

  Usage:  
      
      cyc-status <id>
  
  Example output: 
    
    $ cyc-status 70808
    
    Queens Park Sports Centre

    Status A:  Out of service
    Status B:  Available

#### pod-status - shows status of a selected Pod-Point chargepoint

  Usage:  
      
      pod-status <id>
  
  Example output: 
    
    $ pod-status st-helens-retail-park-kdxd
    St. Helens Retail Park

    Status A:  Available
    Status B:  In use

![](https://scontent-lhr3-1.xx.fbcdn.net/v/t1.0-9/52432290_10157265707852112_4163778606570405888_n.jpg?_nc_cat=111&_nc_ht=scontent-lhr3-1.xx&oh=42a736e93a3d921114875829f2fd6a14&oe=5D17CDFC)

gnuplot.config    simple timeline graph

    gnuplot < gnuplot.config > usage.png
    
![](https://i.imgur.com/zsDuboD.png)

![](https://scontent-lhr3-1.xx.fbcdn.net/v/t1.0-9/52793050_10157265708122112_3410643824790208512_n.jpg?_nc_cat=110&_nc_ht=scontent-lhr3-1.xx&oh=5584488b423b92515a9030c29f449b36&oe=5D1B2007)

