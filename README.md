# D_Conis_ILostMyPhone
This is Assignment M02, which will engage in attention generating behavior and inform the curious onlooker about how to get it back to the owner.
_______________________________________________________________________________________________________
Here Lies the Preproduction Recipe:
  Model - Attributes
    TimeTillAlarm
    OwnerData
    StateOfPhonePossessionVariable { OK , NOK , Recovery }
    *GPS coordinates of phone
  
  View - User Interface
    ShowAttractiveLunchScreen
    ShowDefaultScreen
    ShowAlarmScreen
    ShowIAmFoundScreen
    ShowIAmFonundButNotReturned ( Owner Data and Reward )
    GetSetDelayTime
    GetSnoozeDelay
    GetRecoveryAlarmStop
    GetHardReset 
  
  Controller - Logic / Methods 
    PassDelayTimeToModel
    PassSnoozeDelayToModel
    PassRecovereryAlarmStopToModel
    PassHardResetToModel
    InferLosedOrFoundStatus
    PassAndSoundAlarmToView
    *Send GPS coordinates or Maps Info To Recovery Account  
    InitiateAlarm
    CeaseAlarm
    DoNothing
    
    
    
    
    
