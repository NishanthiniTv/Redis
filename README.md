# Redis

  This redis file is on the Library management application which includes the details about student access, staff access, details about the book and including the return report.
These informations includes:
      
        1.student id ,student name, city, department
        2.book id, title, author, year of publication
        3.staff name, staff id, customer id, department
        4.book id, return customer id, status
        
 This includes four attributes:
        
        1.STUD_ACCESS :This details about the student
        2.BOOKS : This is to know the details of the book and name of the author
        3.STAFF_DETAILS:This details about the staff
        4.RETURN_REPORT:This tells about customer who have taken the book and status of the book
        
 The data is stored as a set with entity name as set names and attribute name as key followed by values .Each set has over three attributes with values associated with it.
