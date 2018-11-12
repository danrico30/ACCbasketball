# ACCbasketball
Basketball predictions
ri <- (1+wi)/(2+ti)
#data

Virginia<-c(33,31,2)
Duke<- c(33,26,7)
Clemson<-c(32,23,9)

#create intitital ranking
BasicW<- function(ti,wi){
  ri<-(1+wi)/(2+ti) 
  return (ri)
}

InitialRanking<-function(x){
wins<-BasicW(x[1],x[2])
print (wins)
}

InitialRanking(Clemson)


#calculate strenghth of schedule

