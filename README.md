# NWTB-GROUP-7
Networking 200B Group 7
Java Project (Church Registration Management System)

 private final String Driver = "com.mysql.cj.jdbc.Driver";
    private final String DatabaseName = "church_management_system";
    private final String DatabaseUser = "root";
    private final String DatabasePassword = "";
    private final String url = "jdbc:mysql://" + DatabaseUser + ":" + DatabasePassword + "@" + "localhost/" + DatabaseName;
    
table names below
registration(id(PRIMARY), firstname, surname, email, address, contact, username, password
choir(choirID(PRIMARY), surname, firstname, gender, gender, dob, occupation, maritalStatus, address, username,password)
youth(youthID(PRIMARY), surname, firstname, gender, dob, occupation, maritalStatus, address, username, password)
meninfellowhip(menID(PRIMARY), surname, firstname, gender, dob, occupation, maritalStatus, address, username, password)
womeninfelllowship(womenID(PRIMARY), surname, firstname, gender, dob, occupation, maritalStatus, address, username, password)
