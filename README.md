# DateFormatter
Easy way to change date format and convert Date to StringDate, Date to Milliseconds, DateString To Date

//Date To String Date convert 

String date = DateUtils.convertDateStringToString("Enter Date Here", "dd MMM yyyy HH:mm:ss", "dd MMM yyyy hh:mm a");

//millisecond To String Date convert 

String date = DateUtils.millisToDate("Enter MilliSecond Here", "yyyy-MM-dd hh:mm:ss");

//Date to millisecond convert 
long millisecond = DateUtils.converDatetomillis("Enter Date Here", "dd MMM yyyy HH:mm:ss");
